 
This project is about hosting a static website. In this project I deployed a static to AWS 
by performing the following steps.
*** Created a public S3 bucket and uploaded website files to my bucket.
*** Next I configured the bucket for website hosting and secured it using IAM policies. 
*** Then sped up content delivery using content distribution network service (CloudFront)
*** Finally accessed my website in a browser.

Attached to this RREADME file is are screenshot of several stages hosting a static website
on S3 and accessing the cached website pages using cloudfront content delivery network(CDN)
service.

Below you will find the CloudFront domain name URL,website end point URL and S3 object end
point URL

http://funbistatic-bucket.s3-website-us-east-1.amazonaws.com
   
https://d1qhaqbrn7pjtv.cloudfront.net

 https://funbistatic-bucket.s3.amazonaws.com/index.html