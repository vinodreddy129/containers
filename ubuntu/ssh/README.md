# SSH Container

This image is an example of how to install and setup SSH for your Docker containers.
It is as simple as:
1. Installing `openssh-server`
1. Adding the ssh user. In this example, we use `ubuntu`, but you can customize this
1. Launching a cluster with your SSH Public Key
1. Run `sudo service ssh start` to start the SSH server
1. On your machine, run `ssh ubuntu@<HOSTNAME> -p 2200 -i <private_key_file_path>`

