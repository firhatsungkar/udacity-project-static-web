Deploy Static Website on AWS

In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.

## URL
CloudFront URL: [http://project-812478677815-static-web.s3-website-ap-southeast-1.amazonaws.com/](http://project-812478677815-static-web.s3-website-ap-southeast-1.amazonaws.com/)
Error Page: [http://project-812478677815-static-web.s3-website-ap-southeast-1.amazonaws.com/404.html](http://project-812478677815-static-web.s3-website-ap-southeast-1.amazonaws.com/404.html)
S3 bucket URL: [https://project-812478677815-static-web.s3.ap-southeast-1.amazonaws.com/](https://project-812478677815-static-web.s3.ap-southeast-1.amazonaws.com/)

## Screenshot

1. Create S3 bucket
![image screenshot](./img/screenshots/1-create-s3-bucket.png)
2. Uploadd S3 bucket
![image screenshot](./img/screenshots/2-upload-s3-bucket.png)
2.1. S3 bucket in the AWS Management console
![image screenshot](./img/screenshots/2.1-s3-management-console.png)
2.2. all the website files uploaded to the newly created S3 bucket.
![image screenshot](./img/screenshots/2.2-file-on-the-s3-bucket.png)
3. Change permission s3 bucket
![image screenshot](./img/screenshots/3-change=permission-s3-bucket.png)
4. Change property s3 bucket
![image screenshot](./img/screenshots/4-change-property-s3-bucket.png)
5. Create Cloudfront distribution
![image screenshot](./img/screenshots/5-create-cloudfront-distribution.png)
5.1 CloudFront Distribution list
![image screenshot](./img/screenshots/5.1-list-of-cloudfront-distribution.png)
