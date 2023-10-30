
 - Install Node.js
 - cd into folder
 - npm install
 - node index.js

we can now use this Dockerfile to build container using 
- docker build . -t app1

to run the container use
- docker run -p 3000:3000 app1
