
# MongoDB

## First of all, Why MongoDb ?

If you have worked with any real-time application, you must have stumbled
across the task of storing data. Traditionally, data storage has been carried out in
well-defined rows and tables. But lately, a shift has been observed towards a
more flexible approach.

To counter the traditional issues of upgrades in table-based databases like SQL
(Structured Query Language), a language called NoSQL was introduced. NoSQL
(Not Only SQL) does not strictly follow a schema and is basically a large object
with multiple smaller nested objects that act as individual rows of data. Many
database systems support this concept, but MongoDB has been one of the
front-runners in this for quite some time now.

### How to Learn MongoDB
MongoDB is a complex and powerful database system that exploits
the benefits of a NoSQL database, so it is important to understand
its purpose and features before we dive into learning its dynamics.

### What is MongoDB?
MongoDB is a cross-platform NoSQL-based database system. It is used for
storing data of all types — strings, numbers, and characters. The main reason
why MongoDB is different from a traditional, structured database is MongoDB
does not follow any strict rules for organizing data.

MongoDB is an instance of a NoSQL database, meaning unlike SQL, MongoDB
does not define tables and columns to categorize and store data. Instead, data in
NoSQL databases are structured in the form of nested JavaScript Object Notation
(JSON) Objects. JSON objects can have any type of member variables, including
other JSON objects. This is how a typical JSON object looks like:

```bash
{ prop1: "val1", prop2: 2, prop3: { prop4: true } }
```

Simple types of values can be stored in a JSON object similar to prop1 and prop2.
Other JSON objects can be stored as well, similar to how prop3 holds a new
JSON object with its own set of properties and values.

In MongoDB, each object is called a document. An array of such documents
creates a collection. A list of such collections constitutes the entire database. The
above structure is flexible enough to allow on-the-fly changes in individual
documents, and scalable enough due to the fact it is simply a dynamic array of
simple objects.

### Features of MongoDB
MongoDB offers multiple features as a powerful NoSQL database. Here are some
of them:
1. Flexibility with Schema
2. Powerful Indexing
3. High Scalability
4. Improved Redundancy
5. High Performance
6. What is MongoDB Used for?
7. Product Data Management
8. Operational Intelligence
9. Content Management Systems

## Steps for learning MongoDB

## [Introduction to NoSQL](https://www.mongodb.com/presentations/back-to-basics-webinar-1-introduction-to-nosql)

We start the series by taking a look at NoSQL and why you should care. We
will cover the differences between the main types of NoSQL databases -
document stores, wide column stores, and key value stores.  

## [Your First MongoDB Application.](https://www.mongodb.com/presentations/back-to-basics-webinar-2-your-first-mongodb-application)

Next, we explore the details of how to build an application in MongoDB. We
will cover the types of entities that we work with in a document database, as
well as how to build document-based applications and how to manage
performance, including the role of indexes.

## [Schema Design, Thinking in Documents](https://www.mongodb.com/presentations/back-to-basics-webinar-3-schema-design-thinking-in-documents)

In the third part of our series, we take a deeper look at the challenges of
schema design. We will explore how to map relational schema into MongoDB,
and how to optimize schema design for reads and writes. Finally, we’ll take a
look at an interesting and unique feature of MongoDB - document validation.

## [Advanced Indexing, Text and Geospatial Indexes](https://www.mongodb.com/presentations/back-to-basics-webinar-4-advanced-indexing-text-and-geo-spatial-indexes)

One of the key value propositions of MongoDB is its advanced library of
indexing techniques. In this webinar we outline how to tune indexes. We then
look at our text index capabilities which allow us to do free text searching
within fields in the database, and our geospatial capabilities which allow you
to search based on location

## [Introduction to the Aggregation Framework](https://www.mongodb.com/presentations/back-to-basics-webinar-5-introduction-to-the-aggregation-framework)

The aggregation framework is one of the most powerful analytical tools
available for MongoDB. In the fifth part of our series we explore how to create
a pipeline of operations that can reshape and transform your data and apply a
range of analytics functions and calculations to produce summary results
across a data set.

## [Production Deployment](https://www.mongodb.com/presentations/back-to-basics-webinar-6-production-deployment)

In the final talk of the series we will explain how we create a stable production
environment. You will learn how to create MongoDB production deployments
that can survive many different failure scenarios. You will also learn how to
create a scalable cluster than can handle any increase in the production
workload.

We will also introduce some of the production deployment tools that we can
use to automate management and deployment.

The whole series will be recorded and made available for review by all
participants. If after attending these bite sized pieces of training you want to
dig deeper we recommend you look at our extensive program of free training
at [MongoDB University](https://university.mongodb.com/).

# Learning MongoDB

Given that MongoDB is a robust document-based database solution, it is important to
know how to use it to the fullest. Following is a list of resources to help you get started:

## [MongoDb Official Documentation](https://www.mongodb.com/cloud/atlas/lp/try2-in?utm_source=google&utm_campaign=gs_apac_india_search_brand_atlas_desktop&utm_term=mongodb%20docs&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=6501677905)

### The Best MongoDB Courses. 

MongoDB is an open-source library, and a lot of developers have tried to create content
to easily help you get started. Let’s take a look at the free and paid video courses that
are available for MongoDB:

## How Long Does it Take to Learn MongoDB?

Given that MongoDB is a powerful and detailed database management solution, you will
probably need about three weeks to get a good start in it. Continued practice, aided with
sample projects for a duration of another one to two weeks is adequate to make the
basics pretty clear in your mind, thereby allowing you to unleash the full potential of this
solution.

However, if you are looking to learn MongoDB for a professional engagement, you may
want to invest six weeks straight to get fully comfortable with MongoDB, Atlas, and the
Mongo Shell.

# Top MongoDB Project Ideas & Topics
### 1. Content Management System
Clubbing the content assets like text and HTML into a single database helps provide a
better user experience. MongoDB has an excellent toolset not only for storing and
indexing but also for controlling the structure of a content management system. You can
easily design a web-based CMS by using the model proposed by “Metadata and Asset
Management” in MongoDB. Additionally, you can use “Storing Comments” to model
user comments on blog posts.
### 2. Gaming Project
Data is an essential part of making video games work. Some typical examples of
gaming data include player profiles, matchmaking, telemetry, and leaderboards.

The common thread between all games is that they all have a specific goal. And you
have to achieve multiple objectives or pay your way out to reach the end goal. This may
involve steps like watering your plants, growing vegetables, serving food in a restaurant,
and so on.
### 3. File Sharing System
You can take up a project to create a system for storing and sharing files, such as
Dropbox or Google Drive. Such services are useful for saving and retrieving data
without having to load large files into memory.

For this project, you can write the server on Node.js and save the files in the MongoDB
program using GridFS..
Now, you can access information from random sections by performing a wide range of
queries on these GridFS files. You can even “skip” to the middle of a video or audio file.
### 4. Metadata Project
Metadata provides information about other data. Some basic metadata examples
include author, date created, date modified, file size, etc. Suppose you hold metadata
from a set of images recorded from 100 cameras. Also, each camera gives 100,000
images in a day, and the records are kept for 30 days in each camera.

By using the MongoDB database, you can simplify and speed up this entire process.
The program would allow you to categorize or aggregate the data into hour-wise,
day-wise, or camera-wise collections. You can also easily scale this implementation
horizontally. For this reason, designing a metadata schema is one of the most-preferred
MongoDB project ideas among students.
### 5. Logging Application
Servers produce a large number of event logs containing useful information such as
errors, warnings, user behavior, etc. Most servers store this data in plain-text log files in
their local systems. Plain-text logs are readable and accessible, but this default method
is not without its limitations. It is difficult to use, reference, and analyze large event
streams without a holistic system










#### Contributed by Suraj Chandramouli.
[![portfolio](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse2.mm.bing.net%2Fth%3Fid%3DOIP.ZT8yItNrXwj4FRWXz5Lf8AHaD4%26pid%3DApi&f=1)](https://github.com/SURAJ-CHANDRAMAULI)



  