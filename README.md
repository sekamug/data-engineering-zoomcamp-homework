# data-engineering-zoomcamp-homework
# Homework 1: Docker, SQL and Terraform
<pre>
#code in the Dockerfile
FROM python:3.12.8
  
#specify the entrypoint
ENTRYPOINT ["bash"]

##to build the image
docker build -t python-bash .

##check pip version within the container
pip --version

</pre>
