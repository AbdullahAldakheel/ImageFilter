# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

#About
 - A microservice that takes an image URL then returns a manipulated image without saving it.
 
# Installation
```
npm i
npm run dev
```
# Usage
```
GET: /filteredimage?image_url={{image_url}}
```

Deployed URL: http://image-filter-dev22.us-east-1.elasticbeanstalk.com/