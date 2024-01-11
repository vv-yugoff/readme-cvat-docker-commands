# readme-cvat-docker-commands

## Docker commands I use most often to run cvat

### "docker load -i container.tar"
This command is used to unpack the docker container for further use

### "scp user@192.168.0.1:/home/user/cvat.tar.gz ~/downloads/projects/cvat"
This command helps you download an archive or file from the server to your computer

### "sudo netstat -tuln | grep 8002"
The command above allows you to look at the desired port and make sure whether it is busy or not?

### "ssh user@192.168.0.1 "cd /home/user && tar -czf cvat.tar.gz cvat""
The command above allows you to connect to the server and archive the desired directory
