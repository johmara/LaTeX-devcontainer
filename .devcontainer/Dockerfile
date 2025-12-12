FROM texlive/texlive:latest

# Install Python and pip
RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

# Verify installation
RUN python3 --version && pip3 --version
