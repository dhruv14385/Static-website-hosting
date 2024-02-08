# Static-website-hosting
In the video below, I have shown how to host a static website on S3 with custom domain name.  

[![Image Alt Text Here](https://img.youtube.com/vi/6gMyy19DVew/0.jpg)](https://www.youtube.com/watch?v=6gMyy19DVew)  

Overview of steps as below  
* Create S3 bucket with “top10” as a sub-domain
* Allow public access
*	Enable Static website hosting
*	Upload index and error files to S3 bucket. 
*	Update Bucket policy to allow access from your domain
*	Go to Route 53 hosted zone and  select your domain name
*	Create record -> Define simple record
*	Add your subdomain, record type a nd select Route traffic to S3 bucket 

