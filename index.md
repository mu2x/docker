# Dcoker file repository
### centos+ssh

% docker build --file Dockerfile .
docker build -t vk --file Dockerfile . #build the docker image 'vk'
docker run -t -d vk # run the docker image 'vk'
