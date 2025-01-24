# data-engineering-zoomcamp-homework
<pre>
# repo for homework1
#code in the Dockerfile
FROM python:3.12.8
##specify the entrypoint
ENTRYPOINT ["bash"]

##to build the image
docker build -t python-bash .

##check pip version within the container
pip --version

</pre>
