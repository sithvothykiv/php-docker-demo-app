
# PHP Docker Demo App
This is a PHP demo application. 


## Resources Dockerhub

https://hub.docker.com/r/sithvothykiv/docker-php-helloworld
#

## Get Started 🚀  
To get started, Run docker command 

   
## Usage  
~~~javascript  
docker pull sithvothykiv/docker-php-helloworld

docker image ls

docker run -t -p 8000:80 docker-php-helloworld

<img width="1286" alt="Screenshot 2022-12-22 at 3 53 57 pm" src="https://user-images.githubusercontent.com/34917417/209096097-b5a84438-e217-4c0b-b7e8-870d327326b0.png">

![Screenshot 2022-12-22 at 3 55 02 pm](https://user-images.githubusercontent.com/34917417/209096244-1a938ae3-71c0-4f07-8d3e-e076822373d8.png)

~~~  
  
## Authors  
- [@sithvothykiv](https://www.github.com/sithvothykiv)  
 
 
## Todo Features  
- Create dockerfile
- Build Docker image
- Push to dockerhub
- Showing run instruction on dockerhub
 
## Run Locally  
Clone the project  

~~~bash  
  git clone https://github.com/sithvothykiv/php-docker-demo-app.git
~~~

Go to the project directory  

~~~bash  
  cd php-docker-demo-app
~~~

Pull Repository from DockerHub  

~~~bash  
docker build -t php-docker-demo-app .

docker image ls

docker run -p 8000:8000 -d <imageID>

