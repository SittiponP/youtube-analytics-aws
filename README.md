# youtube-analytics-aws
## Architecture Diagram

![img](https://github.com/darshilparmar/dataengineering-youtube-analysis-project/blob/main/architecture.jpeg)

### Project Overview
This project is aims to manage, streamline, and perform analysis on the youtube data based on the video categories and the trending metrics

### Services we be using
1. Amazon S3: for the storage dataset
2. AWS IAM: for manage the access control of our project
3. AWS GLUE: for preparing and combine data for analytics
4. AWS lambda: for computing service and run code without creating or managing servers
5. AWS Athena: Athena is query service using with S3
6. Quick Sight: is a Amazon service for making a dashboard built for the cloud

### Dataset Used
The dataset that used in this project is from the kaggle it contains statistics on daily popular Youtube videos 

https://www.kaggle.com/datasets/datasnaek/youtube-new

### Example Dashboard
![img](https://github.com/SittiponP/youtube-analytics-aws/blob/main/my_dashboard.png)