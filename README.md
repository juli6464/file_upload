# Getting Started with File upload with multer in Node js
This Demo was uploading image and video file using multer middleware. 
Create in root, a carpet with name called image
## Original Repository
https://github.com/happy-bhesdadiya/file-upload

## Requisites
Install first nodemon for this project

## Project Setup
In the project directory, you can run:

### `npm init`
### `npm install`
### `npm start`

Runs the app in the development mode.

## Calling the single image upload API
- Open Postman and create POST request for image upload
- URL will be [localhost:3000/uploadImage](http://localhost:3000/uploadImage)
- select Body in menus then select form-data
- In table write the key name `image` and select type as a `file`
- then after select any image `(file will only png|jpg, size less then 1MB)`
- And Send the request.

## Calling the Bulk image upload API
- The process will be same as the single image upload
- Just change two things
- URL will be [localhost:3000/uploadBulkImage](http://localhost:3000/uploadBulkImage)
- Change kay name as a images and select multiple images.`(Select only 4 images)`
- Send the request

