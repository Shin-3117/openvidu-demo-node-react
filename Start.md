# docker
docker run -p 4443:4443 --rm -e OPENVIDU_SECRET=MY_SECRET openvidu/openvidu-dev:2.29.0

# node server
cd openvidu-tutorials/openvidu-basic-node
node index.js

# react
cd openvidu-call-react/openvidu-call-react
npm start
