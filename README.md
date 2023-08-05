# Docker-multi-stage-build

⚡*Reduce the Docker image size by 800%*⚡

🔍 Are you tired of large image files slowing down your website's loading speed? Do you want to enhance user experience without compromising on image quality? Look no further! 

👉Here we Done the task with the help of *Multi-Stage-Docker-Build* Concept- The size of docker image is reduced upto by 800%-- which boosts the site's performance , efficiency and also make it easy to transport the container.

*But how will it be possible---lets understand ---*

At the time creation of Docker file , we split the docker file in 2 or more stages depending upon complexity of application.
1)- BUILD stage--
In build stage we install application base image along with all its libraries and dependencies.
2)-RUN/EXECUTE stage--
Here is the cache, here we only add application runtime and copy the DOCKER application binary from build stage along with entrypoint.

And than create the image ----*This eliminates unnecessary dependencies and files from the final image*

⚫Here are some advantages of using multi-stage Docker builds:---
🛠️Improved Security
🚀 Faster Builds
🚀 Optimized for CI/CD
🔑 Easier Debugging
📈 Reduced Image Size
