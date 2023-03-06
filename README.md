# AWS-Redshift
Core concept: \
	Cluster \
	Node: Leader node, Compute nodes \
	Storage \
	Node slices \
	Database 

# The second time of Redshift on 3/2/2023
Redshit introduction: \
https://learn.acloud.guru/course/aws-certified-big-data-specialty/learn/e576d80a-0495-4a08-fa97-b539da26fd79/c6b70c73-b1b1-a3d3-8226-bc06e55f1af3/watch 

# Compression 
https://learn.acloud.guru/course/aws-certified-big-data-specialty/learn/e576d80a-0495-4a08-fa97-b539da26fd79/c6b70c73-b1b1-a3d3-8226-bc06e55f1af3/watch 

# Workload management
Manage and limit user's resource. \
https://learn.acloud.guru/course/aws-certified-big-data-specialty/learn/e576d80a-0495-4a08-fa97-b539da26fd79/5775675e-62c5-ecaa-3b5c-0e0050fcebd9/watch 

# Load data into Redshift
Can load data into Redshift from s3/Dynamodb/emr using copy command. \
https://learn.acloud.guru/course/aws-certified-big-data-specialty/learn/e576d80a-0495-4a08-fa97-b539da26fd79/42a18bc8-bb0e-36e2-f160-098ac82714ec/watch 


# Security
# Audit
https://docs.aws.amazon.com/redshift/latest/mgmt/db-auditing.html \
https://aws.amazon.com/premiumsupport/knowledge-center/redshift-audit-logging/ \
Disable by default. \
Stores: system tables --> S3 --> CloudWatch, based on configure. 
Three types of events: connection, user log(changes to database user), user activity log. In default, connection and user 
are enabled when audit on. To enable user activity, change the parameter enable_user_activity_logging.
