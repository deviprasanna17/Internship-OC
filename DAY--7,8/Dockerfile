FROM python:3.8

# copy the requirements file into the image
# switch working directory
WORKDIR /app

# install the dependencies and packages in the requirements file
RUN pip3 install flask

# copy every content from the local file to the image
COPY . /app

# configure the container to run in an executed manner

CMD ["python3","app.py"]
