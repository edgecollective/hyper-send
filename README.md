# Hyper-send

## Install Docker

https://docs.docker.com/install/linux/docker-ce/ubuntu/

## Use hyper-send

Build the Docker container using:

> ./build.sh

Then run with:

> ./run.sh

This will auto-generate a new public key, printed out to the console

You will need this public key when swarming with 'hyper-receive'

If you type something into the terminal while 'hyper-send' is running, and hit return, that content will be added to the hypercore, broadcast, and should be replicated on any computer that is running 'hyper-receive'.  

