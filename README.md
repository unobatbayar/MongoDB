<div align="center">
  <h1><code>mongo-db</code></h1>

  <strong>Learning Mongo-DB.</strong>

<h3>
    <a href="https://github.com/unobatbayar/mongo-db/pull/new/master">Contribute</a>
  </h3>
  
  <sub> Built by <a href="https://www.twitter.com/unobatbayar">unobatbayar</a> to learn MongoDB for Semi-structured Data and Advanced Data Modelling ECS650U at <a href="https://www.qmul.ac.uk"> Queen Mary University of London</a>.  </sub>
</div>

## MongoDB
 A free and open-source cross-platform document-oriented database
 
 
## -- Local --

## Install MongoDB 
      brew install mongodb

## Run 
      mongo 
(The directory and installation has already been made for my personal computer, and I'm using a macbook pro. However, if you would like to do it for your use please refer to: https://docs.mongodb.com/manual/installation/) 

## -- Cloud --

MongoDB Atlas requires no payments and can be used instantly upon creating an account -> https://cloud.mongodb.com
Create an username and password with Read/Write permission and use them in below code to connect directly. Make sure you add your current IP address, otherwise it will be rejected.

## Run

      mongo "mongodb://airline-shard-00-00-tq7q4.mongodb.net:27017,airline-shard-00-01-tq7q4.mongodb.net:27017,airline-shard-00-02-tq7q4.mongodb.net:27017/test?replicaSet=Airline-shard-0" --ssl --authenticationDatabase admin --username <USERNAME> --password <PASSWORD>
      
<sub>Give feedback, ideas and more: <br> <sub> 
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/unobatbayar.svg?style=social&label=Follow%20%40unobatbayar)](https://twitter.com/unobatbayar)

