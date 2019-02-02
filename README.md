# Neural Networks and Deep Learning

[![Deep Learning Ai](https://d3njjcbhbojbot.cloudfront.net/api/utilities/v1/imageproxy/https://coursera-course-photos.s3.amazonaws.com/e5/801ef077e311e79b5e257ef20b3a76/deeplearningai.png?auto=format%2Ccompress&dpr=2&w=256&h=32)](https://d3njjcbhbojbot.cloudfront.net/api/utilities/v1/imageproxy/https://coursera-course-photos.s3.amazonaws.com/e5/801ef077e311e79b5e257ef20b3a76/deeplearningai.png?auto=format%2Ccompress&dpr=2&w=256&h=32)

Experiments and concepts of Deep Learning.


### Usage
First of all, build the container using docker-compose and then you can 
access the Jupyter that is ready to be used.

#### Run with docker compose
```sh
cd neural-networks-deep-learning
docker-compose up -d
```

#### Accessing Jupyter
```sh
http://<your-ip>:8888/tree
```

#### Ports
```sh
    - 8888 => Jupyter
```

### DockerHub
```sh
https://hub.docker.com/r/maciomatheus/jupyter_notebook_data_science/
