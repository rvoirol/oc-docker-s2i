# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# Changing parameters of the Dockfile to generate a new outup in OCP pod.
# CMD ["/bin/bash", "-c", "sleep infinity"]
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
