# Dcoker file repository
### centos+ssh

- docker build --file Dockerfile .
- docker build -t vk --file Dockerfile . #build the docker image 'vk'
- docker run -t -d vk # run the docker image 'vk'
- docker run -t -p 80:80  -d -v C:/Users/vkric/"OneDrive - University of Texas at El Paso"/COURSES_Assessment_Website:/onedrive vk
