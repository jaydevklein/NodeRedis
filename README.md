## Description
Two JavaScript files exist here. They are meant to be run individually to show the response time when using Redis.  
- `node app.js` - API query without Redis caching  
- `node appWithRedis.js` - API query with Redis caching  

## Test
http://localhost:3000  

## Prerequisites
- Install Dependencies:  
`npm install`  

- Install redis-server:  
To use Redis on Windows https://redislabs.com/blog/redis-on-windows-8-1-and-previous-versions/  


* Open a separate Command prompt to start the Redis server before running the Node script.