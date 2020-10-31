# github.io
I hosted this HTML website by configuring Apache Web Server on Amazon Linux EC2 instance.
Made document root persistent by mounting /var/www/html on EBS block device.
Stored static objects used in code ( like background image) in S3.
Set up CDN( Content Delivery Network) using Cloudfront ( domain origin as S3 bucket) to solve the problem of low latency.  


