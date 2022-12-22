
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

docker build -t docker-php-helloworld .

docker run -t -p 8000:80 docker-php-helloworld

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

