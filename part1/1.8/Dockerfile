# Start from the alpine image
FROM ubuntu:18.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

# Copy the hello.sh file from this location to /usr/src/app/ creating /usr/src/app/hello.sh.
COPY command.sh .

# Execute a command with `/bin/sh -c` prefix.
RUN touch additional.txt

# When running docker run the command will be ./hello.sh
CMD ./command.sh