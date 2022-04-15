# AWS-resilient-fault-tolerant-wordpress
Built out a FANCY souped up blog site

Here is my latest project learning AWS. I strictly followed the lab instructions, but I’d like to tell you all about it. I utilized CloudFormation to make templates for creating useful pieces of infrastructure: Virtual Private Cloud, EC2 servers, backed-up Database, caching (to improve performance), a file structure (for things like pictures), a load balancer (to make sure servers are not overloaded), an autoscaling group (to increase capacity when all you LinkedIn folks devour this savory content), and CloudFront (a global content delivery network). I optimized a dummy WordPress site to make this well-architected blog application. The result is a resilient, fault tolerant system built on AWS!

This is a diagram of what I built:

![wordpress-diagram](https://user-images.githubusercontent.com/66890519/163630275-b4e78c69-6b4b-4f79-81bf-538c3f16574d.png)

Here is a picture of the eventual WordPress Page

![wordpress-screenshot](https://user-images.githubusercontent.com/66890519/163592226-8edf6c4c-18e2-4a81-aa37-296a33e2121e.png)
