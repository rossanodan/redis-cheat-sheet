# Redis Cheat Sheet

- [Redis Cheat Sheet](#redis-cheat-sheet)
  - [What is Redis?](#what-is-redis)
  - [Redis CLI](#redis-cli)
  - [Redis in NodeJS](#redis-in-nodejs)
  - [Resources](#resources)

## What is Redis?

Redis **is a type of database** and more specificaly is a NoSQL database. It's not like the other NoSQL databases or like a SQL database (such as MongoDB, PostgreSQL or MySQL) because Redis doesn't have the concept of "document" nor of "table".

All of the data in Redis is stored in **key, value pairs**. Think about Redis as one big giant JSON file.

![Redis database as JSON file](./images/image-1.png)

Unlike the other databases than run on disk, **Redis runs on RAM** (on memory) and this makes it **very fast** but also volatile.

This is why Redis is generally used for caching: it has to be accessed often and it has to be quick.

## Redis CLI
## Redis in NodeJS
## Resources
- [https://redis.io/](https://redis.io/)
- [Redis Crash Course on YouTube](https://www.youtube.com/watch?v=jgpVdJB2sKQ&t=17s&ab_channel=WebDevSimplified)