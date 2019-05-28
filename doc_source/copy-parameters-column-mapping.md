# Column Mapping Options<a name="copy-parameters-column-mapping"></a>

By default, COPY inserts values into the target table's columns in the same order as fields occur in the data files\. If the default column order will not work, you can specify a column list or use JSONPath expressions to map source data fields to the target columns\. 
+ [Column List](#copy-column-list)
+ [JSONPaths File](#copy-column-mapping-jsonpaths)

## Column List<a name="copy-column-list"></a>

You can specify a comma\-separated list of column names to load source data fields into specific target columns\. The columns can be in any order in the COPY statement, but when loading from flat files, such as in an Amazon S3 bucket, their order must match the order of the source data\. 

When loading from an Amazon DynamoDB table, order does not matter\. The COPY command matches attribute names in the items retrieved from the DynamoDB table to column names in the Amazon Redshift table\. For more information, see [Loading Data from an Amazon DynamoDB Table](t_Loading-data-from-dynamodb.md)

 The format for a column list is as follows\.

```
COPY tablename (column1 [,column2, ...]) 
```

If a column in the target table is omitted from the column list, then COPY loads the target column's [DEFAULT](r_CREATE_TABLE_NEW.md#create-table-default) expression\.

If the target column does not have a default, then COPY attempts to load NULL\.

If COPY attempts to assign NULL to a column that is defined as NOT NULL, the COPY command fails\. 

If an [IDENTITY](r_CREATE_TABLE_NEW.md#identity-clause) column is included in the column list, then [EXPLICIT_IDS](copy-parameters-data-conversion.md#copy-explicit-ids) must also be specified; if an IDENTITY column is omitted, then EXPLICIT\_IDS cannot be specified\. If no column list is specified, the command behaves as if a complete, in\-order column list was specified, with IDENTITY columns omitted if EXPLICIT\_IDS was also not specified\.

## JSONPaths File<a name="copy-column-mapping-jsonpaths"></a>

When loading from data files in JSON or Avro format, COPY automatically maps the data elements in the JSON or Avro source data to the columns in the target table by matching field names in the Avro schema to column names in the target table or column list\.

If your column names and field names don't match, or to map to deeper levels in the data hierarchy, you can use a JSONPaths file to explicitly map JSON or Avro data elements to columns\. 

For more information, see [JSONPaths file](copy-parameters-data-format.md#copy-json-jsonpaths)\. 