ARG version
FROM almalinux:${version:-9}

# default version i have given as 9 , you can override the version in runtime/build time 
# command-----> docker build -t <image name>:v1 --build-arg version=8 .

ARG trainer=mamatha
ARG duration=120hr
ENV duration=${duration}
ENV course=devops
RUN echo "courese is:${course},trainer is:${trainer},duration is: ${duration}"
CMD [ "sleep", "500" ]  
