# NodeAPIAdaptor
Generate Node-API interface declarations and calls using reflection.

## Introduction
Node-API is a protocol for communicating between Node.js and native cpp libraries.  
Using Node-API, you can build a wrapper around your native cpp libraries and generate a dynamic library called `addon`.  
For more information on Node-API, see [Node-API](https://nodejs.org/api/n-api.html) and [node-addon-api](https://github.com/nodejs/node-addon-api).  

But what if your native cpp libraries have a lot of interfaces that need to be exposed?  
That's gonna be a lot of work, and this is where `NodeAPIAdaptor` comes in.
Using `NodeAPIAdaptor`, you can generate Node-API interface declarations and calls so much easier.

