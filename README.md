 ## Dockerizing the django app
 
 Clone the repo

  ```bash 
  git clone https://github.com/praneshp1org/dockerizing-django-app.git
  ```
 Build the docker image using the command

  ```bash 
  docker build .

  ```
Run the container using port mapping
  ```bash
  docker run -p 8000:8000 -it <image_id>
  ```

[Watch the tutorial on YouTube](https://youtu.be/CIkal80mSME)
