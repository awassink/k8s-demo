FROM gcr.io/google_containers/hyperkube-arm:v1.2.0

# Install required packages
RUN apt-get update && apt-get install -y -q \
        nfs-common \
        glusterfs-client \
     && rm -rf /var/cache/apt/* /var/lib/apt/lists/*

