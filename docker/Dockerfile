FROM tensorflow/tensorflow:1.0.0.2-gpu
RUN apt-get update
RUN apt-get install -y python-tk
WORKDIR /app
RUN echo "LD_LIBRARY_PATH='$LD_LIBRARY_PATH:/usr/lib/x86_64-linux-gnu_custom'" >> ~/.profile
RUN echo "LD_LIBRARY_PATH='$LD_LIBRARY_PATH:/usr/lib/x86_64-linux-gnu_custom'" >> ~/.bashrc
COPY ./ /app