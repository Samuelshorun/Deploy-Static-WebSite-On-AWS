# Deploy-Static-WebSite-On-AWS-With-S3-Bucket-And-CloudFront
Travel Blog

Steps 
1. Create a public S3 bucket and upload the website files to your bucket.

![Static Hosting](https://user-images.githubusercontent.com/32329381/169233836-eea286f4-4feb-4833-b4c0-ea5b3fad94a3.PNG)

[S3 Bucket Files](https://user-images.githubusercontent.com/32329381/169232850-32d8ddc7-bd0c-4f52-bb1b-aba37836e351.PNG)

2. Configure the bucket for website hosting and secure it using IAM policies.

![Bucket Policy Editor](https://user-images.githubusercontent.com/32329381/169233126-094f3a1b-e854-40b4-b2ac-9c0414440142.PNG)



3. Speed up content delivery using AWS’s content distribution network service, CloudFront.

![Cloud Front](https://user-images.githubusercontent.com/32329381/169232746-8c1960e1-7365-4f6a-90a3-7722ce264423.PNG)


access  website in a browser using the unique CloudFront endpoint.

![d1v0m6drc73nil cloudfront net](https://user-images.githubusercontent.com/32329381/169233460-616b4fcf-574c-412f-a741-8df14514b16b.PNG)

Copy Right @ ALX-Udacity
