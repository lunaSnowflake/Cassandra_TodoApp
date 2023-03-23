<!--- STARTEXCLUDE --->
# JAMStack + Netlify + Astra DB + Cassandra
*10 minutes, Beginner, [Start Building](https://github.com/DataStax-Examples/todo-astra-jamstack-netlify#quick-start)*

This is an example React To-Do application using a [DataStax Astra](https://dtsx.io/2Yhvqtv) free tier database.
<!--- ENDEXCLUDE --->

![image](https://raw.githubusercontent.com/DataStax-Examples/todo-astra-jamstack-netlify/master/hero.png)

## Quick Start
<!--- STARTEXCLUDE --->
0) [Signup for DataStax Astra](https://dtsx.io/2Yhvqtv), or login to your already existing account. 
<!--- ENDEXCLUDE --->
1) [Create an Astra DB Database](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-astra-db) or use an existing one.
2) [Create an Astra DB Keyspace](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-astra-db-keyspace) called `sag_todo_jamstack` in your database.
3) [Generate an Application Token](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-application-token) with the role of `Database Administrator` for the Organization that your Astra DB is in.
4) Click the 'Open in Gitpod' link: [![Open in IDE](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/DataStax-Examples/todo-astra-jamstack-netlify)
5) Once the app is finished launching in the Gitpod IDE, copy the `.env.example` file to a file named `.env` and fill the required values in from your Application Token and [Astra DB connection settings](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#get-your-astra-db-connection-settings).
6) Start the example by running `npm run dev` in the Gitpod console.

## Objectives
* Provide a fullstack development example using Astra DB as the storage backend

## How this works
Once the Astra DB credentials are provided, the necessary tables are created in the database. The webservice will be available on port 8888 once the application has been deployed.

[JAMstack](https://jamstack.org/) is a big leap forward in how we can write web applications that are easy to write, deploy, scale, and also maintain. Using this approach means that newly created content is rendered from a content API, while a static render of it is being built into the site for future.
