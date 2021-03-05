---
title: Amazon Web Services (AWS)
section: deployment
order: 0
hidden: true
---

Amazon Web Services offers reliable, scalable, and inexpensive cloud computing services. Free to join, pay only for what you use.

AWS is also one of the most popular choices for hosting a Spree application. There are several services you can use to host Spree on AWS, here we're briefly touch upon those options.

## AWS Elastic Beanstalk

The easiest way to run Spree or any other Ruby on Rails application on AWS is through AWS Elastic Beanstalk which is comparable to Heroku PaaS (Platform as a Service).

This is the recommended approach if you're just starting up. 

## AWS 

## Other AWS services

* [AWS RDS](https://aws.amazon.com/rds/) - Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. Spree works great with multiple databases: [Amazon Aurora (both MySQL and PostgreSQL variants)](https://aws.amazon.com/rds/aurora/), [RDS PostgreSQL](https://aws.amazon.com/rds/postgresql/), [RDS MySQL](https://aws.amazon.com/rds/mysql/) and [RDS MariaDB](https://aws.amazon.com/rds/mariadb/)
* [AWS ElastiCache Redis](https://aws.amazon.com/elasticache/redis/?nc=sn&loc=2&dn=1) - we recommend setting up a Redis database for [Active Job background queue](https://guides.rubyonrails.org/active_job_basics.html), which we use for sending out transactional emails
* [AWS ElastiCache Memcached](https://aws.amazon.com/elasticache/memcached/?nc=sn&loc=2&dn=1) - we recommend using [Memcached as a cache storage](https://guides.rubyonrails.org/caching_with_rails.html) to increase performance and scalability of your Spree application
