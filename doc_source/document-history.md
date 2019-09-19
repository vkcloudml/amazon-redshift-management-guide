# Document History<a name="document-history"></a>

The following table describes the important changes in each release of the *Amazon Redshift Cluster Management Guide* after June 2018\. For notification about updates to this documentation, you can subscribe to an RSS feed\.

 **API version: 2012\-12\-01** 

 **Latest documentation update: September 19, 2019** 

For a list of the changes to the *Amazon Redshift Database Developer Guide*, see [Amazon Redshift Database Developer Guide Document History](https://docs.aws.amazon.com/redshift/latest/dg/doc-history.html)\.

For more information about new features, including a list of fixes and the associated cluster version numbers for each release, see [Cluster Version History](http://docs.aws.amazon.com/redshift/latest/mgmt/rs-mgmt-cluster-version-notes.html)\. 

| Change | Description | Date | 
| --- |--- |--- |
| [Cluster release version](http://docs.aws.amazon.com/redshift/latest/mgmt/rs-mgmt-cluster-version-notes.html) | Release notes for a new cluster release version are available\. For more information, see [Cluster Version History](http://docs.aws.amazon.com/redshift/latest/mgmt/rs-mgmt-cluster-version-notes.html)\. | September 19, 2019 | 
| [Security information updates](http://docs.aws.amazon.com/redshift/latest/mgmt/iam-redshift-user-mgmt.html) | Updates to the security information documentation\. | June 24, 2019 | 
| [Snapshot enhancements](http://docs.aws.amazon.com/redshift/latest/mgmt/working-with-snapshots.html) | Amazon Redshift now supports several enhancements to managing and scheduling snapshots\. | April 4, 2019 | 
| [Concurrency scaling](http://docs.aws.amazon.com/redshift/latest/mgmt/workload-mgmt-config.html) | You can configure workload management \(WLM\) to enable concurrency scaling mode\. For more information, see [Configuring Workload Management](http://docs.aws.amazon.com/redshift/latest/mgmt/workload-mgmt-config.html)\. | March 21, 2019 | 
| [Updated JDBC and ODBC drivers](https://docs.aws.amazon.com/redshift/latest/mgmt/connecting-to-cluster.html) | Amazon Redshift now supports new versions of the JDBC and ODBC drivers\. For more information, see [Configure a JDBC Connection](https://docs.aws.amazon.com/redshift/latest/mgmt/configure-jdbc-connection.html) and [Configure and ODBC Connection](https://docs.aws.amazon.com/redshift/latest/mgmt/configure-odbc-connection.html)\. | February 4, 2019 | 
| [Deferred Maintenance](https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-clusters.html#rs-mgmt-defer-maintenance) | If you need to reschedule your cluster’s maintenance window, you have the option to defer maintenance by up to 14 days\. If we need to update hardware or make other mandatory updates during your period of deferment, we notify you and make the required changes\. Your cluster isn't available during these updates\. For more information, see [Deferring Maintenance](https://docs.aws.amazon.com/redshift/latest/mgmt/managing-clusters-console.html#defer-maintenance-window)\. | November 20, 2018 | 
| [Advance Notification](https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-events.html) | Amazon Redshift provides notification in advance for some events\. These events have an event category of `pending`\. For example, we send an advance notification if a hardware update is required for one of the nodes in your cluster\. You can subscribe to pending events the same as other Amazon Redshift events\. For more information, see [Subscribing to Amazon Redshift Event Notifications](https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-event-notifications.html#working-with-event-notifications-subscribe)\. | November 20, 2018 | 
| [Elastic Resize](https://docs.aws.amazon.com/redshift/latest/mgmt/rs-resize-tutorial.html#elastic-resize) | Elastic resize is the fastest method to resize a cluster\. Elastic resize adds or removes nodes on an existing cluster, then automatically redistributes the data to the new nodes\. Because it doesn't create a new cluster, the elastic resize operation completes quickly, usually in a few minutes\. For more information, see [Resizing Clusters](https://docs.aws.amazon.com/redshift/latest/mgmt/rs-resize-tutorial.html)\. | November 15, 2018 | 
| [New ODBC drivers](http://docs.aws.amazon.com/redshift/latest/mgmt/configure-odbc-connection.html) | Amazon Redshift ODBC drivers have been updated to version 1\.4\.3\.1000\. For more information, see [Configure an ODBC Connection](http://docs.aws.amazon.com/redshift/latest/mgmt/configure-odbc-connection.html)\.  | November 8, 2018 | 
| [Cancel resize operation](http://docs.aws.amazon.com/redshift/latest/mgmt/rs-resize-tutorial.html#rs-tutorial-resize-operation-overview) | You can now cancel a resize operation while it is in progress\. For more information, see [Resize Operation Overview](http://docs.aws.amazon.com/redshift/latest/mgmt/rs-resize-tutorial.html#rs-tutorial-resize-operation-overview)\. | November 2, 2018 | 
| [Modify cluster to change encryption](http://docs.aws.amazon.com/redshift/latest/mgmt/changing-cluster-encryption.html) | You can modify an unencrypted cluster to use AWS Key Management Service \(AWS KMS\) encryption, using either an AWS\-managed key or a customer\-managed key \(CMK\)\. When you modify your cluster to enable KMS encryption, Amazon Redshift automatically migrates your data to a new encrypted cluster\. You can also migrate an unencrypted cluster to an encrypted cluster by modifying the cluster\. | October 16, 2018 | 
| [Amazon Redshift Spectrum supports Enhanced VPC Routing](https://docs.aws.amazon.com/redshift/latest/mgmt/spectrum-enhanced-vpc.html) | You can now use Redshift Spectrum with Enhanced VPC Routing enabled for your cluster\. You might need to perform additional configuration steps\. For more information, see [Using Amazon Redshift Spectrum with Enhanced VPC Routing](https://docs.aws.amazon.com/redshift/latest/mgmt/spectrum-enhanced-vpc.html)\.  | October 10, 2018 | 
| [Query Editor](https://docs.aws.amazon.com/redshift/latest/mgmt/query-editor.html) | You can now run SQL queries from the Amazon Redshift Management Console\.  | October 4, 2018 | 
| [Workload Execution Breakdown chart](https://docs.aws.amazon.com/redshift/latest/mgmt/analyze-workload-performance.html) | You can now get a detailed view of your workload's performance by looking at the Workload Execution Breakdown chart in the console\. For more information, see [Analyzing Workload Performance](https://docs.aws.amazon.com/redshift/latest/mgmt/analyze-workload-performance.html)\. | July 30, 2018 | 
| [Maintenance tracks](https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-clusters.html#rs-mgmt-maintenance-tracks) | You can now determine if your cluster will always be updated to the latest version of Amazon Redshift or to a previous version by choosing a maintenance track\. For more information, see [Choosing Cluster Maintenance Tracks](https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-clusters.html#rs-mgmt-maintenance-tracks)\.  | July 26, 2018 | 
| [Updated JDBC and ODBC drivers](https://docs.aws.amazon.com/redshift/latest/mgmt/configure-odbc-connection.html) | Amazon Redshift now supports new versions of the JDBC and ODBC drivers\. For more information, see [Configure a JDBC Connection](https://docs.aws.amazon.com/redshift/latest/mgmt/configure-jdbc-connection.html) and [Configure and ODBC Connection](https://docs.aws.amazon.com/redshift/latest/mgmt/configure-odbc-connection.html)\. | July 13, 2018 | 
| [On\-demand cluster release versions](http://docs.aws.amazon.com/redshift/latest/mgmt/working-with-clusters.html#rs-mgmt-cluster-version) | You can now upgrade your cluster to the latest release version as soon as it is available\. For more information, see [Manage Cluster Versions](http://docs.aws.amazon.com/redshift/latest/mgmt/working-with-clusters.html#rs-mgmt-cluster-version)\.  | June 29, 2018 | 

The following table describes the important changes to the *Amazon Redshift Cluster Management Guide* before July 2018\.


| Change | Description | Release Date | 
| --- | --- | --- | 
| New CloudWatch metrics | New CloudWatch metrics added for monitoring query performance\. For more information, see [Amazon Redshift Performance Data](metrics-listing.md) | May 17, 2018 | 
|   New JDBC and ODBC drivers   |   Amazon Redshift JDBC drivers have been updated to version 1\.2\.12\.1017\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\. Amazon Redshift ODBC drivers have been updated to version 1\.4\.1\.1001\. For more information, see [Configure an ODBC Connection](configure-odbc-connection.md)\.   |   March 7, 2018   | 
|  HSM encryption  | Amazon Redshift supports only AWS CloudHSM for hardware security module \(HSM\) key management\. For more information, see [Amazon Redshift Database Encryption](working-with-db-encryption.md)\.  |  March 6, 2018  | 
| IAM Role Chaining | If an IAM role attached to your cluster doesn't have access to the necessary resources, you can chain another role, possibly belonging to another account\. Your cluster then temporarily assumes the chained role to access the data\. You can also grant cross\-account access by chaining roles\. Each role in the chain assumes the next role in the chain, until the cluster assumes the role at the end of chain\. You can chain a maximum of 10 roles\. For more information, see [Chaining IAM Roles in Amazon Redshift](authorizing-redshift-service.md#authorizing-redshift-service-chaining-roles)\. | February 23, 2018 | 
| New DC2 node types | The new generation of dense compute \(DC\) node types offer much better performance at the same price as DC1\. To take advantage of performance improvements, you can migrate your DC1 cluster to the newer DC2 node types\. For more information, see [Clusters and Nodes in Amazon Redshift](working-with-clusters.md#rs-about-clusters-and-nodes)\. | October 17, 2017 | 
|  New JDBC drivers  |  Amazon Redshift JDBC drivers have been updated to version 1\.2\.10\.1009\. Also, JDBC version 4\.2 drivers are now supported\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\.  |  October 16, 2017  | 
| ACM certificates | Amazon Redshift is replacing the SSL certificates on your clusters with AWS Certificate Manager \(ACM\) issued certificates\. ACM is a trusted public certificate authority \(CA\) that is trusted by most current systems\. You might need to update your current trust root CA certificates to continue to connect to your clusters using SSL\. For more information, see [Transitioning to ACM Certificates for SSL Connections](connecting-transitioning-to-acm-certs.md)\. | September 18, 2017 | 
| Service\-linked roles | A service\-linked role is a unique type of IAM role that is linked directly to Amazon Redshift\. Service\-linked roles are predefined by Amazon Redshift and include all the permissions that the service requires to call AWS services on behalf of your Amazon Redshift cluster\. For more information, see [Using Service\-Linked Roles for Amazon Redshift](using-service-linked-roles.md)\. | September 18, 2017 | 
| IAM database user authentication | You can configure your system to permit users to create user credentials and log on to the database based on their IAM credentials\. You can also configure your system to let users sign on using federated single sign\-on \(SSO\) through a SAML 2\.0\-compliant identity provider\. For more information, see [Using IAM Authentication to Generate Database User Credentials](generating-user-credentials.md)\. | August 11, 2017 | 
| New JDBC and ODBC drivers | The new JDBC and ODBC drivers support IAM database user authentication\. Amazon Redshift JDBC drivers have been updated to version 1\.2\.7\.1003\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\. Amazon Redshift ODBC drivers have been updated to version 1\.3\.6\.1000\. For more information, see [Configure an ODBC Connection](configure-odbc-connection.md)\. | August 11, 2017 | 
| Table\-level restore supports Enhanced VPC Routing | Table\-level restore is now supported on clusters that use [Enhanced VPC Routing](enhanced-vpc-routing.md)\. For more information, see [Restoring a Table from a Snapshot](working-with-snapshots.md#working-with-snapshot-restore-table-from-snapshot)\. | July 19, 2017 | 
| Query Monitoring Rules | Using WLM query monitoring rules, you can define metrics\-based performance boundaries for WLM queues and specify what action to take when a query goes beyond those boundaries—log, hop, or abort\. You define query monitoring rules as part of your workload management \(WLM\) configuration\. For more information, see [Configuring Workload Management](workload-mgmt-config.md)\. | April 21, 2017 | 
|  New JDBC and ODBC drivers  |  Amazon Redshift JDBC drivers have been updated to version 1\.2\.1\.1001\. Also, JDBC version 4\.2 drivers are now supported\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\. Amazon Redshift ODBC drivers have been updated to version 1\.3\.1\.1000\. For more information, see [Configure an ODBC Connection](configure-odbc-connection.md)\.  |  November 18, 2016  | 
|  Enhanced VPC Routing  |  When you use Amazon Redshift Enhanced VPC Routing, Amazon Redshift forces all [COPY](https://docs.aws.amazon.com/redshift/latest/dg/r_COPY.html) and [UNLOAD](https://docs.aws.amazon.com/redshift/latest/dg/r_UNLOAD.html) traffic between your cluster and your data repositories through your Amazon VPC\. For more information, see [Amazon Redshift Enhanced VPC Routing](enhanced-vpc-routing.md)\.  |  September 15, 2016  | 
|  New JDBC Drivers  |  Amazon Redshift JDBC drivers have been updated to version 1\.1\.17\.1017\. Also, JDBC version 4\.2 drivers are now supported\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\.  |  July 5, 2016  | 
| New Connection Log fields | The [Connection Log](db-auditing.md#db-auditing-connection-log) audit log has two new fields to track SSL connections\. If you routinely load audit logs to an Amazon Redshift table, you will need to add the following new columns to the target table: sslcompression and sslexpansion\. | May 5, 2016 | 
|  New ODBC drivers  |  Amazon Redshift ODBC drivers have been updated to version 1\.2\.7\.1007\. For more information, see [Configure an ODBC Connection](configure-odbc-connection.md)\.  |  March 30, 2016  | 
|  IAM Roles for COPY and UNLOAD  | You can now specify one or more AWS Identity and Access Management \(IAM\) roles that your cluster can use for authentication to access other AWS services\. IAM roles provide a more secure alternative to provide authentication with COPY, UNLOAD, or CREATE LIBRARY commands\. For more information, see [Authorizing Amazon Redshift to Access Other AWS Services on Your Behalf](authorizing-redshift-service.md) and [Authorizing COPY, UNLOAD, and CREATE EXTERNAL SCHEMA Operations Using IAM Roles](copy-unload-iam-role.md)\.  | March 29, 2016 | 
| Restore from Table |  You can restore a table from a cluster snapshot to a new table in an active cluster\. For more information, see [Restoring a Table from a Snapshot](working-with-snapshots.md#working-with-snapshot-restore-table-from-snapshot)\.  |  March 10, 2016  | 
|  New JDBC Drivers  |   Amazon Redshift JDBC drivers have been updated to version 1\.1\.10\.1013\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\. You can now set the SSLMode property to specify whether the driver verifies host names when validating TLS/SSL certificates\. For more information, see [JDBC Driver Configuration Options](configure-jdbc-options.md)\.  |  February 18, 2016  | 
|  Using IAM Condition in policies  |  You can further restrict access to resources by using the Condition element in IAM policies\. For more information, see [Using IAM Policy Conditions for Fine\-Grained Access Control](redshift-iam-access-control-overview.md#redshift-policy-resources.conditions)\.  |  December 10, 2015  | 
| Modify Publicly Accessible |  You can modify an existing cluster in a VPC to change whether it is publicly accessible\. For more information, see [Modifying a Cluster](managing-clusters-console.md#modify-cluster)\.  |  November 20, 2015  | 
|  New JDBC Drivers  |  Amazon Redshift JDBC drivers have been updated to version 1\.1\.10\.1010\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\.  Amazon RedshiftODBC drivers have been updated to version 1\.2\.6\.1006\. For more information, see [Configure an ODBC Connection](configure-odbc-connection.md)\.  |  November 19, 2015  | 
|  Documentation Fixes  |  Published various documentation fixes\.   |  August 28, 2015  | 
|  Documentation Update  | Updated troubleshooting guidance about configuring network settings to ensure that hosts with different maximum transmission unit \(MTU\) sizes can determine the packet size for a connection\. For more information, see [Queries Appear to Hang and Sometimes Fail to Reach the Cluster](connecting-drop-issues.md)\.  |  August 25, 2015  | 
|  Documentation Update  | Revised entire section about parameter groups for better organization and clarity\. For more information, see [Amazon Redshift Parameter Groups](working-with-parameter-groups.md)\.  |  August 17, 2015  | 
|  New JDBC Drivers  |  Amazon Redshift JDBC drivers have been updated to version 1\.1\.7\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\.   |  August 14, 2015  | 
|  WLM Dynamic Properties  | The WLM configuration parameter now supports applying some properties dynamically\. Other properties remain static changes and require that associated clusters be rebooted so that the configuration changes can be applied\. For more information, see [WLM Dynamic and Static Properties](workload-mgmt-config.md#wlm-dynamic-and-static-properties) and [Amazon Redshift Parameter Groups](working-with-parameter-groups.md)\.  |  August 3, 2015  | 
| Copy KMS Encrypted Clusters to Another Region | Added content about configuring snapshot copy grants to enable copying of AWS KMS\-encrypted clusters to another region\. For more information, see [Copying AWS KMS\-Encrypted Snapshots to Another AWS Region](working-with-db-encryption.md#configure-snapshot-copy-grant)\.  |  July 28, 2015  | 
|  Documentation Update  | Updated the database encryption section to better explain how Amazon Redshift uses AWS KMS or HSMs for managing keys, and how the encryption process works with each of these options\. For more information, see [Amazon Redshift Database Encryption](working-with-db-encryption.md)\.  |  July 28, 2015  | 
|  New JDBC Drivers  |   Amazon Redshift JDBC drivers have been updated to version 1\.1\.7\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\.   |  July 2, 2015  | 
|  New Node Type  | Amazon Redshift now offers a new node type, DS2\. Updated documentation references to existing node types to use new names introduced in this release\. Also revised the section to better explain the node type combinations and clarify default quota limits\. For more information, see [Clusters and Nodes in Amazon Redshift](working-with-clusters.md#rs-about-clusters-and-nodes)\.  |  June 9, 2015  | 
| Reserved Node Offerings | Added content about new reserved node offerings\. Also revised the section to better explain and compare the available offerings, and provided examples to demonstrate how on\-demand and reserved node pricing affect billing\. For more information, see [Overview](purchase-reserved-node-instance.md#purchase-reserved-node-offering-overview)\.  |  June 9, 2015  | 
| New ODBC Drivers |  Amazon Redshift ODBC driver have been updated\. Added a section for previous versions of these drivers and a link to release notes for the drivers\. For more information, see [Configure an ODBC Connection](configure-odbc-connection.md)\.   |  June 5, 2015  | 
|  Documentation Fixes  |  Published various documentation fixes\.   |  April 30, 2015  | 
|  Documentation Update  |  Updated the download links to new versions of the Amazon Redshift JDBC drivers, and added a section for previous versions of these drivers\. Also added a link to release notes for the drivers\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\.   |  April 1, 2015  | 
|  Documentation Update  |  Added downloads for new versions of the Amazon Redshift JDBC drivers\. Also updated the format of the Amazon Redshift JDBC URL\. For more information, see [Configure a JDBC Connection](configure-jdbc-connection.md)\. Added cluster security group ingress rules as a taggable resource\. For more information, see [Tagging Resources in Amazon Redshift](amazon-redshift-tagging.md)\. Updated the instructions for adding a cluster security group ingress rule, and added instructions for tagging a cluster security group ingress rule\. For more information, see [Managing Cluster Security Groups Using the Console](managing-security-groups-console.md)\.  |  March 16, 2015  | 
| New Feature |  This release of Amazon Redshift introduces new ODBC and JDBC drivers optimized for use with Amazon Redshift\. For more information, see [Connecting to an Amazon Redshift Cluster Using SQL Client Tools](connecting-to-cluster.md)\.   |  February 26, 2015  | 
|  New Feature  |  This release of Amazon Redshift introduces cluster performance metrics that allow you to view and analyze query execution details\. For more information, see [Viewing Query Performance Data](performance-metrics-queries.md)\.  |  February 26, 2015  | 
|  Documentation Update  |  Added a new example policy that demonstrates granting permission to common AWS service actions and resources on which Amazon Redshift relies\. For more information, see [Customer Managed Policy Examples](redshift-iam-access-control-identity-based.md#redshift-iam-accesscontrol.examples)\.  |  January 16, 2015  | 
|  Documentation Update  |  Updated guidance about setting the maximum transmission unit \(MTU\) to disable TCP/IP jumbo frames\. For more information, see [Supported Platforms to Launch Your Cluster](working-with-clusters.md#cluster-platforms) and [Queries Appear to Hang and Sometimes Fail to Reach the Cluster](connecting-drop-issues.md)\.  |  January 16, 2015  | 
|  Documentation Update  |  Revised the content about the `wlm_json_configuration` parameter, and provided example syntax to configure this parameter by using the AWS CLI on the Linux, Mac OS X, and Microsoft Windows operating systems\. For more information, see [Configuring Workload Management](workload-mgmt-config.md)\.  |  January 13, 2015  | 
|  Documentation Update  |  Added missing event notifications and descriptions\. For more information, see [Amazon Redshift Event Categories and Event Messages](working-with-event-notifications.md#redshift-event-messages)\.  |  January 8, 2015  | 
|  Documentation Update  |  Updated guidance about IAM policies for Amazon Redshift actions and resources\. Revised the section to improve organization and clarity\. For more information, see [Security in Amazon Redshift](iam-redshift-user-mgmt.md)\.  |  November 21, 2014  | 
|  New Feature  |  This release of Amazon Redshift introduces the ability to encrypt clusters using encryption keys from AWS Key Management Service \(AWS KMS\)\. AWS KMS combines secure, highly available hardware and software to provide a key management system scaled for the cloud\. For more information about AWS KMS and encryption options for Amazon Redshift, see [Amazon Redshift Database Encryption](working-with-db-encryption.md) and [Managing Clusters Using the Console](managing-clusters-console.md)\.  |  November 12, 2014  | 
|  New Feature  |  This release of Amazon Redshift introduces the ability to tag resources, such as clusters and snapshots\. Tags enable you to provide user\-defined metadata to categorize your billing reports based on cost allocation, and to help you better identify resources at a glance\. For more information, see [Tagging Resources in Amazon Redshift](amazon-redshift-tagging.md)\.  |  November 4, 2014  | 
|  New Feature  |  Increased the maximum node limit to 128 nodes for dw1\.8xlarge and dw2\.8xlarge node sizes\. For more information, see [Clusters and Nodes in Amazon Redshift](working-with-clusters.md#rs-about-clusters-and-nodes)\.   |  October 30, 2014  | 
|  Documentation Update  |  Added links to the Microsoft Visual C\+\+ 2010 Redistributable Packages that are required for Amazon Redshift to use PostgreSQL ODBC drivers\. For more information, see [Install and Configure the Amazon Redshift ODBC Driver on Microsoft Windows Operating Systems](install-odbc-driver-windows.md)\.   |  October 30, 2014  | 
|  New Feature  |  Added the ability to terminate queries and loads from the Amazon Redshift console\. For more information, see [Viewing Query Performance Data](performance-metrics-queries.md) and [Viewing Cluster Metrics During Load Operations](performance-metrics-loads.md)\.   |  October 28, 2014  | 
|  Documentation Fixes  |  Published various documentation fixes\.  |  October 17, 2014  | 
|  New Content  |  Added content about shutting down clusters and deleting clusters\. For more information, see [Shutting Down and Deleting Clusters](working-with-clusters.md#rs-mgmt-shutdown-delete-cluster) and [Deleting a Cluster](managing-clusters-console.md#delete-cluster)\.   |  August 14, 2014  | 
|  Documentation Update  |   Clarified the behavior of the **Allow Version Upgrade** setting for clusters\. For more information, see [Overview](working-with-clusters.md#working-with-clusters-overview)\.   |  August 14, 2014  | 
|  Documentation Update  |  Revised procedures, screenshots, and organization of topic about working with clusters in Amazon Redshift console\. For more information, see [Managing Clusters Using the Console](managing-clusters-console.md)\.  |  July 11, 2014  | 
|  New Content  |  Added a new tutorial about resizing Amazon Redshift clusters, including how to resize a cluster while minimizing the amount of time that the cluster is in read\-only mode\. For more information, see [Resizing Clusters in Amazon Redshift](rs-resize-tutorial.md)\.  |  June 27, 2014  | 
|  New Feature  |  Added the ability to rename clusters\. For more information, see [Renaming Clusters](working-with-clusters.md#rs-mgmt-rename-cluster) and [Modifying a Cluster](managing-clusters-console.md#modify-cluster)\.  |  June 2, 2014  | 
|  Documentation Update  |  Updated the \.NET code example to use the ODBC data provider when connecting to a cluster programmatically by using \.NET\. For more information, see [Connecting to a Cluster by Using \.NET](connecting-in-code.md#connecting-in-code-dotnet)\.   |  May 15, 2014  | 
|  New Feature  |  Added options to select a different parameter group and security group when you restore a cluster from a snapshot\. For more information, see [Restoring a Cluster from a Snapshot](managing-snapshots-console.md#snapshot-restore)\.   |  May 12, 2014  | 
|  New Feature  |  Added new section to describe how to configure a default Amazon CloudWatch alarm to monitor the percentage of disk space used in an Amazon Redshift cluster\. This alarm is a new option in the cluster creation process\. For more information, see [Default Disk Space Alarm](working-with-clusters.md#rs-clusters-default-disk-usage-alarm)\.  |  April 28, 2014  | 
|  Documentation Update  |  Clarified information about Elliptic curve Diffie—Hellman Exchange \(ECDHE\) support in Amazon Redshift\. For more information, see [Connect Using SSL](connecting-ssl-support.md#connect-using-ssl)\.  |  April 22, 2014  | 
|  New Feature  |  Added statement about Amazon Redshift support for the Elliptic curve Diffie—Hellman \(ECDH\) key agreement protocol\. For more information, see [Connect Using SSL](connecting-ssl-support.md#connect-using-ssl)\.  |  April 18, 2014  | 
|  Documentation Update  | Revised and reorganized the topics in the [Connecting to an Amazon Redshift Cluster Using SQL Client Tools](connecting-to-cluster.md) section\. Added more information about JDBC and ODBC connections, and a new troubleshooting section for connection issues\. | April 15, 2014 | 
|  Documentation Update  |   Added version in IAM policy examples throughout the guide\.   |  April 3, 2014  | 
|  Documentation Update  |   Added information about how pricing works when you resize a cluster\. For more information, see [Purchasing Amazon Redshift Reserved Nodes](purchase-reserved-node-instance.md)\.   |  April 2, 2014  | 
|  New Feature  |  Added a section about a new parameter, `max_cursor_result_set_size`, which sets the maximum result set size, in megabytes, that can be stored per individual cursor\. This parameter value also affects the number of concurrently active cursors for the cluster\. For more information, see [Amazon Redshift Parameter Groups](working-with-parameter-groups.md)\.  |  March 28, 2014  | 
|  New Feature  |  Added explanation about the **Cluster Version** field now including both cluster engine version and database revision number\. For more information, see [Amazon Redshift Clusters](working-with-clusters.md)\.  |  March 21, 2014  | 
|  New Feature  |  Updated the resize procedure to show the new resize progress information on the cluster's **Status** tab\. For more information, see [Resizing a Cluster](managing-clusters-console.md#resizing-cluster)\.  |  March 21, 2014  | 
|  Documentation Update  | Reorganized and updated [What Is Amazon Redshift?](welcome.md) and revised [Amazon Redshift Management Overview](overview.md)\. Published various documentation fixes\. | February 21, 2014 | 
|  New Feature  |  Added new node types and sizes for Amazon Redshift clusters, and rewrote the related cluster overview topic for better organization and clarity based on feedback\. For more information, see [Amazon Redshift Clusters](working-with-clusters.md)\.  |  January 23, 2014  | 
|  New Feature  |  Added information about using elastic IP \(EIP\) addresses for publicly\-accessible Amazon Redshift clusters in virtual private clouds\. For more information about EIP in Amazon Redshift, see [Managing Clusters in an Amazon Virtual Private Cloud \(VPC\)](managing-clusters-vpc.md) and [Creating a Cluster in a VPC](getting-started-cluster-in-vpc.md)\.  |  December 20, 2013  | 
|  New Feature  |  Added information about the AWS CloudTrail logs for Amazon Redshift\. For more information about Amazon Redshift support for CloudTrail, see [Logging Amazon Redshift API Calls with AWS CloudTrail](db-auditing.md#rs-db-auditing-cloud-trail)\.  |  December 13, 2013  | 
|  New Feature  |  Added information about the new user activity log and the `enable_user_activity_logging` database parameter for the database audit logging feature in Amazon Redshift\. For more information about database audit logging, see [Database Audit Logging](db-auditing.md)\. For more information about database parameters, see [Amazon Redshift Parameter Groups](working-with-parameter-groups.md)\.   |  December 6, 2013  | 
|  New Feature  |  Updated to describe configuring Amazon Redshift to automatically copy automated and manual snapshots to a secondary region\. For more information about configuring cross\-region snapshot copy, see [Copying Snapshots to Another Region](working-with-snapshots.md#cross-region-snapshot-copy)\.  |  November 14, 2013  | 
|  New Feature  |  Added section to describe Amazon Redshift audit logging for connection and user activity, and storing these logs in Amazon S3\. For more information about database audit logging, see [Database Audit Logging](db-auditing.md)\.  |  November 11, 2013  | 
|  New Feature  |  Added section to describe Amazon Redshift encryption with new features for managing encryption keys in a hardware security module \(HSM\) and rotating encryption keys\. For more information about encryption, HSM, and key rotation, see [Amazon Redshift Database Encryption](working-with-db-encryption.md), [Encryption for Amazon Redshift Using Hardware Security Modules](working-with-db-encryption.md#working-with-HSM), and [Encryption Key Rotation in Amazon Redshift](working-with-db-encryption.md#working-with-key-rotation)\.  |  November 11, 2013  | 
|  New Feature  |  Updated to describe publishing notifications of Amazon Redshift events by using Amazon SNS\. For information about Amazon Redshift event notifications, see [Amazon Redshift Event Notifications](working-with-event-notifications.md)\.  |  November 11, 2013  | 
|  New Feature  |  Updated to describe IAM resource level permissions\. For information about Amazon Redshift IAM permissions, see [Security in Amazon Redshift](iam-redshift-user-mgmt.md)\.  |  August 9, 2013  | 
|  New Feature  |  Updated to describe restore progress metrics\. For more information, see [Restoring a Cluster from a Snapshot](working-with-snapshots.md#working-with-snapshot-restore-cluster-from-snapshot)\.  |  August 9, 2013  | 
|  New Feature  |  Updated to describe cluster snapshot sharing and create snapshot progress metrics\. For more information, see [Sharing Snapshots](working-with-snapshots.md#working-with-snapshot-share-snapshot)\.  |  July 17, 2013  | 
|  Documentation Fixes  |  Published various documentation fixes\.   |  July 8, 2013  | 
|  New Console Screens  |  Updated the *Amazon Redshift Cluster Management Guide* to match changes in the Amazon Redshift console\.   |  April 22, 2013  | 
|  New Guide  |  This is the first release of the *Amazon Redshift Management Guide*\.   |  February 14, 2013  | 