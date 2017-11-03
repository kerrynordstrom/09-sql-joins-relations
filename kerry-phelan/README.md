![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 09: Database Relationships & SQL Joins
===

## Submission Instructions
Follow the submission instructions from day 1.

## Resources  
[SQLBolt](http://sqlbolt.com/) -- Interactive SQL Tutorial

[SQL Cheat Sheet](http://www.cheat-sheets.org/sites/sql.su/)

[Query String Primer](https://en.wikipedia.org/wiki/Query_string)

## Configuration
_Your repository must include:_
```
09-sql-joins-relations
├── .eslintrc.json
├── .gitignore
├── LICENSE
├── README.md
├── node_modules
├── package-lock.json
├── package.json
├── public
│   ├── data
│   │   └── hackerIpsum.json
│   ├── index.html
│   ├── new.html
│   ├── scripts
│   │   ├── article.js
│   │   └── articleView.js
│   ├── styles
│   │   ├── base.css
│   │   ├── fonts
│   │   │   ├── icomoon.eot
│   │   │   ├── icomoon.svg
│   │   │   ├── icomoon.ttf
│   │   │   └── icomoon.woff
│   │   ├── icons.css
│   │   ├── layout.css
│   │   └── modules.css
│   └── vendor
│       ├── scripts
│       │   ├── handlebars.js
│       │   ├── highlight.pack.js
│       │   └── marked.js
│       └── styles
│           ├── default.css
│           ├── normalize.css
│           └── railscasts.css
└── server.js
```

## Feature Tasks
***Don't forget to set your conString!***

*As a user, I want more dynamic control over my database so that I can relate similar articles.*
- Write the following SQL queries:
  - Join all data from articles and authors tables on the author_id value of each
  - Insert an author
  - Retrieve an author
  - Update an author
  - Insert an article
  - Retrieve an article
  - Update an article


*As a developer, I want to utilize SQL queries so that I can join data together in the database.*
- This means you'll want to be able to do full CRUD on articles in the database. You'll have to use SQL to make a table for articles (**and clear out the table for troubleshooting**), with a class-level method attached to the constructor function (because it does not apply to any single instance). Then teach each article instance how to write or update itself to the database, or delete itself, via instance methods (available for use as needed in the code).
- Crucially, you'll need to trace through the app logic, and all those callback functions to determine WHEN is the right time to load data, or convert JSON.
- Look through the TODOs, which signify areas of the code with varying levels of completeness, and focus initially on writing correct SQL. Once you complete the TODOs, follow the instructions in the adjacent [CRUD-testing.md](CRUD-testing.md) doc to verify that everything works.


## Documentation
_Your README.md must include:_

```md
# Project Name

**Author**: Kerry Nordstrom and Phelan Kerry
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
<!-- We set up this application to create new articles, read existing and newly added articles on page refresh, update the articles and their details, and delete any unnecessary articles if needed.  -->

## Getting Started
<!-- We created SQL queries which will execute to do all of the CRUD operations on our page. -->

## Architecture
<!-- The focus of this lab was demonstrating the CRUD operations as communicated between user client, server controller, and database model.  We used ExpressJS to simplify this process.-->

## Change Log
<!-- 11-3-2017 9:00am - Begin lab with Kerry driving and Phelan navigating.  Began working through setting up the node and SQL environments in terminal.
 +
 +11-3-2017 10:15am - Phelan drove and Kerry navigated.  We tackled most of the TODOs which explained the CRUD operations.
 +
 +11-3-2017 12noon - Kerry drove and Phelan navigated as we debugged and wrote the README.
-->
```
