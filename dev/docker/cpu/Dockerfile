FROM tensorflow/tensorflow:1.15.0-py3

# Install protobug compiler
# sudo apt-get update && install protobuf-compiler git-core

# Add the repos to the docker file and make it the working directory
RUN pip3 install gpt-2-simple jupyter regex requests tqdm numpy toposort pandas click beautifulsoup4 keras matplotlib Pillow

# Enter the Shell
CMD /bin/bash