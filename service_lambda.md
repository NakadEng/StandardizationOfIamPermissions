## Lambdaがさわるサービス
### ストレージ系
S3

S3 Glacier
AWS Backup

### DB系
RDS *Lambda-to-RDSというユースケースは考慮しない？*
DynamoDB
ElastiCache
Neptune
Amazon Redshift
Amazon DocumentDB

### 管理系
CloudWatch
Systems Manager

### 開発系
CodeBuild
CodeDeploy
CodePipeline

### 通知系
Simple Notification Service
Simple Queue Service

## EC2がさわるサービス
### ストレージ系
S3
EFS
FSx
S3 Glacier

### DB系
RDS
DynamoDB
ElastiCache
Neptune
Amazon Redshift
Amazon DocumentDB

### 管理系
CloudWatch
Systems Manager *SessionManagerはDeny*

### 鍵管理
KMS