# harshrajput4343-Docker-Learning
2nd October , learning docker 


 to pull image from dockerHUb : docker pull image-name
 to run the image             : docker run image-name

To run pulled image on docker : docker run -p 8501:8501 image-name  {here 8501-> you are using  and next 8501 is port on which it is running} Port mapping

to build image :        docker build -t reponame  .


to run         :        docker run -p 8501:5000 reponame 


push to docker hub: After checking on personal desktop that container is runninf fine we push it on docker hub
step 1 : docker login
step 2 : docker push conatainer_name

want to pull it from hub
step1: docker pull harshrajput4343/laptop_price
step 2:docker run -p 8501:8501 harshrajput4343/laptop_price

