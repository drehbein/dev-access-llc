Deployment:
 - Local files/git
 - GitHub Actions
 - github-deploy role
 - s3

Email routing:
 - Incoming email to dev-access-llc.com routed to S3 using DNS records
 - AWS SES inserts into table in S3
 - Table insertion triggers SES to send new email from dev-access-llc.com to personal email
