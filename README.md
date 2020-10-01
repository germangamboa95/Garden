# Garden
An API first framework for developers who want to get things done


## Initial Development Goals 

- CLI-Tool: Creating boilerplate files by hand is boring. 
- Core-framework: 
  - Wraps express (http layer should be whatever so no hard coupling) to provide http layer. 
  - Wraps TypeORM with QOL helpers 
  - Provide authentication (probably wrap passport js but later write our own) 
  - Provide authorization, via gates and policies
  - Provide a way to either use custom controllers or no code controllers that just need a model definition 
  - Provide a way to allow for composable actions (solves the people chucking everything into a controller) 
  - Provide a way to serialize responses into various formats 
  - Provide a way that make apps created with this easy to test
   

## Code organiztion 
All initial development will be done in this repository. 
Eventually there will be two repositories one containing the core of the framework and the other a built example. 

## Why 

There seems to be a very big gap between in nodejs land between frameworks like NestJS and just using raw express, koa, or fastify.
While there is some players in this gap such as feathersjs they are not optimal for developing things fast and seem to be overly restrictive. 
The aim of Garden is to provide you with the tools that you need to develop applications fast while staying out of your way. 
