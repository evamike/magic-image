# Magic Image Server

This Node Express project uses OpenAI's deep learning model that generates images from text input and saves shared images to Cloudinary.

## Tools

* Node.js, Express.js  
* OpenAI: The DALL-E deep learning model that generates images from text input.  
* Cloudinary: A cloud-based image storage service.  
* MongoDB: Store posts shared with the community.

## Run the project

* Populate the environment variables needed for 3rd party tools:  
OPENAI_API_KEY  
MONGODB_URL  
CLOUDINARY_CLOUD_NAME  
CLOUDINARY_API_KEY  
CLOUDINARY_API_SECRET  

* Run the below command to start the server on http://localhost:8080.    

```
npm start
```