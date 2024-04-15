# This contains the M10 Assignment 


# Part 1 
## File Loaded in S3 Bucket:
#### First row as blank
S3 URL:-
s3://iaseleniumanupam/charities_bureau_firstrowblank_20240414211736.csv

Amazon Resource Name (ARN): - 
arn:aws:s3:::iaseleniumanupam/charities_bureau_firstrowblank_20240414211736.csv

#### In non-none Format:
S3 URL:- 
s3://iaseleniumanupam/charities_bureau_scrape_2024041421172120240414212523.csv

Amazon Resource Name (ARN): - 
arn:aws:s3:::iaseleniumanupam/charities_bureau_scrape_2024041421172120240414212523.csv

### Part 2
#### All 7 pages data
S3 URL:- 
s3://iaseleniumanupam/charities_bureau_scrape_All_page_data_20240414214911.csv

Amazon Resource Name (ARN): - 
arn:aws:s3:::iaseleniumanupam/charities_bureau_scrape_All_page_data_20240414214911.csv

## S3 Bucket Policy

{
    "Version": "2012-10-17",
    "Id": "Policy1713146529795",
    "Statement": [
        {
            "Sid": "Stmt1713146528031",
            "Effect": "Allow",
            "Principal": "*",
            "Action": [
                "s3:GetObject",
                "s3:PutObject"
            ],
            "Resource": [
                "arn:aws:s3:::iaseleniumanupam/charities_bureau_firstrowblank_20240414211736.csv",
                "arn:aws:s3:::iaseleniumanupam/charities_bureau_scrape_2024041421172120240414212523.csv",
                "arn:aws:s3:::iaseleniumanupam/charities_bureau_scrape_All_page_data_20240414214911.csv"
            ]
        }
    ]
}