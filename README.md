# faceRecognition_api

The application is currently deployed [here](https://face-recognition-cgva.onrender.com/)
It basically uses Clarifai API to recognize a face on the picture you provide as a link to .jpg file and also lets you create your own account by registering and keeping track of the number of face-detections you performed so far. So it's combining many different things!

For deployment, I opted to use render.com as a free tool, which allowed me to deploy the front-end, back-end, and create a PostgreSQL database on the same platform, thereby providing a costless solution. While the course suggests using Heroku for deployment, I found render.com to be more suitable for my needs.

**Note**
The registration functionality is not available anymore due to Postgres limit of 90 days being served for free on Render being breached. Leaving the code nevertheless here so that anybody interested can inspect on their own! Cheers
