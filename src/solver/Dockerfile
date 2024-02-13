# Use a specific version of the GCC image
FROM gcc:13

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the local code to the container
COPY . .

RUN git clone https://github.com/bjs3118/Sliding_puzzle

# Compile the code (if needed, you can run this manually later)
# RUN g++ -o myapp main.cpp

# Default command is an interactive shell
CMD ["/bin/bash"]
