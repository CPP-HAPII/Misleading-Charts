# Amazon Mechanical Turk Resources
*How to create a quiz survey in Amazon Mechanical Turk*

## Set Up a New Project on Mechanical Turk
Mturk Tutorial: https://docs.aws.amazon.com/AWSMechTurk/latest/RequesterUI/CreatingYourBatchofHITs.html

## Database to Hold Images
*Use Amazon S3 to get a link to images that can be accessed in the .csv* <br>
Create S3 bucket: https://docs.aws.amazon.com/AmazonS3/latest/userguide/creating-bucket.html <br>
Configure CORS: https://docs.aws.amazon.com/AmazonS3/latest/userguide/ManageCorsUsing.html <br>
Note: Turn off "block public access" and give read permissions to each object in the bucket
