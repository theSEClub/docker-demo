# Docker Demo
this is a simple docker image

# How to Run:
## 1- Install Docker
### Windows / Linux
https://docs.docker.com/get-docker

### Apple MacOS
https://orbstack.dev


## 2- Download demo
you can download the files from [here](https://github.com/theSEClub/docker-demo/archive/refs/heads/main.zip)\
or clone the repository using `git`\
```git clone https://github.com/theSEClub/docker-demo```


## 3- Open Terminal in the project folder
you can do this by shift + right click `Open in Terminal` in *Windows*\
or use the terminal like a pro 🔥\
```cd docker-demo```


## 4- Build docker image
```docker build . -t seclub-image```


## 5- Run the container
```docker run -p 8000:5000 docker-demo```


## 6- Open the browser
type this url in your browser to see the image working\
```http://localhost:8000```