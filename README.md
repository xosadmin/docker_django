# docker_django
A docker container to run Django programs
  
### How to build own image based on this repo
1. Clone this project
2. use ``docker build -t foo .``, where ``foo`` is your image name
3. Create a new container by the following command:  
   ``docker run -d -p 8000:8000 -v /path/to/your/app:/app foo``
4. Enjoy
  
### Launch new container from Docker Hub  

Use the following command:  
``docker run -d -p 8000:8000 -v /path/to/your/app:/app xosadmin/docker-django:latest``  
