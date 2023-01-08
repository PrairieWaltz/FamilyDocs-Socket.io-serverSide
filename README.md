# FamilyDocs
A family notes/planning app that can be edited in real time by multiple parties. 

![FamilyDoc-Main](https://user-images.githubusercontent.com/85768337/211174933-f7ae97ab-6929-473e-8092-a0993a3ebd68.png)

## Dependencies
```
  "dependencies": {
    "mongoose": "^6.8.3",
    "socket.io": "^4.5.4"
  }
    
  "devDependencies": {
    "nodemon": "^2.0.20"
  }
  ```
  Clone repo and run `npm i` from 'client' directory to install project set-up

## Mongoose Set-Up
Install `MongoDb` and `Mongosh` or preferred database for local use. Mongoose is a great light client for this type of use. 

Spin up your local Db in shell with `mongod`. In new shell run `mongosh` for easy CLI acesss. This will store Docs locally in `google-docs-clone` collection. Once in mongosh run `show dbs` to access all active dbs. Run `use google-docs-clone` to step into correct Db. In this Db run `show collections`. If you have a `documents` collection you're all set up. 
