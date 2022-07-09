
# AlgoDsGo! - Search, simplified.
This is my first project using Node.js where I created a search engine which works on problems of codechef and codeforces and when entered a query it returns most relavant results.

### Deployed App

https://algodsgo.herokuapp.com/




## Quick Setup Guide (locally)
Most Important! -
I am using node module natural@2.4.5 for stemming and removing stopwords. Newer versions of it aren't working. So, install version 2.4.5 of natural.

Follow these steps to set up locally:

1) Download the files locally.
2) Open terminal navigate to project folder - run these commands:

````node
$ npm i express ejs natural@2.4.5 
````
3) File named precomputation.js can use memory which may not be handled by the default node.js allocated memory. To fix it, just run this command in terminal:

````node
$ export NODE_OPTIONS="--max-old-space-size=8192"
````

4) Such memory issue won't be there if only index.js is being run. 
5) Run index.js file to host app locally:
````node
$ npm start index.js
````
6) That's it! App is ready to launched locally🚀

## Key Features
### Filtering
This Search engine also allows users to filter the search type from codechef or codeforces.

![Alt Text](https://github.com/himan17/algodsgo/blob/main/public/images/filters.gif)


