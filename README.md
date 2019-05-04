///////////////////////////////////run static web using Docker////////////////////////////


$ docker build -t <image_name> .   //build image

$ docker run -dit --name <cotainer_name> -p80:80 <image_name>     //run container
