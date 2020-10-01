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
   

