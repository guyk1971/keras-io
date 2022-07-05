FROM tensorflow/tensorflow:latest-gpu
LABEL description="Installs the required environment to run keras examples on gpu"
# the requirements.txt is copied from the keras io repo
COPY requirements.txt ./
RUN /usr/bin/python3 -m pip install --upgrade pip \
    pip install -r requirements.txt



