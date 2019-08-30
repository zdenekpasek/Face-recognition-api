# Face recognition application 
## BACKEND

App url: https://facerecog-application.herokuapp.com/


## Description
- web application for recognizing faces from images
- based on React
- it is possible to register your own account and count score of your already recognized faces
- deployed on heroku

## Used technologies
- javascript ES6 (React)
- ajax (fetch)
- react
- express (server)
- clarifai-api (it returns probability scores on the likelihood that the image contains human faces and coordinate locations      of where those faces appear with a bounding box)
- bcrypt (used for hashing passwords)
- knex (used for easier work with psql database)
- relational database (PostgreSQL)

## Sign in page
![home](https://user-images.githubusercontent.com/45901583/63957516-d0442280-ca88-11e9-8698-d7ae2a839b91.PNG)

## Register page
![register](https://user-images.githubusercontent.com/45901583/63957758-53657880-ca89-11e9-9137-00575b59abd9.PNG)

## Image recog page
![imagetst](https://user-images.githubusercontent.com/45901583/63957764-55c7d280-ca89-11e9-865e-139005ed7978.PNG)
