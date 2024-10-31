## Just for Your Information

This workflow is designed to monitor Nginx, installing (if Nginx doesn't exist in your server) automatically back it up configuration to S3 based on the specified schedule.


You may add your own AWS Access Key and Secret Access Key in this workflow (add it on secret and variables > actions > new repository secret ), or use credentials from another cloud provider that supports `aws s3 sync` or similar commands for syncing and backup. This setup will ensure that the specified files and configurations are automatically synchronized and securely backed up to your chosen cloud storage at regular intervals. and you can change or adding the file or directory that you want to backup.


NOTE : you already have AWS ACCOUNT and S3 bucket for this automations
