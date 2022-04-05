# s3-static-website-in-cloudfront
Description
---------------------------------------------------------------
For a long time, s3 has been an excellent choice for hosting static websites, but it's still a hassle to set up manually, To establish and manage users, buckets, certificates, a CDN, and roughly a hundred additional configuration choices, you must navigate through dozens of pages in the AWS console, it quickly becomes tiresome if you do this repeatedly. Terraform, a well-known "Infrastructure as code" tool, allows us to create resources (such as instances, storage buckets, users, rules, and DNS records)

Comnponents for hosting static website
---------------------------------------
Hosting a static website on S3 only requires a few components. The components are:

(1). S3 bucket for the website files
(2). Cloudfront distribution as CDN
(3). Route53 records for the given domain
