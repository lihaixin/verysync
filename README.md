verysync for docker

docker run --name verysync -d -v /mnt/downloads/verysync:/data -p 8886:8886 --restart unless-stopped jonnyan404/verysync
