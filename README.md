## Docker autosurf container for web service called feelingsurf.fr

## Requirements
* Linux
* Docker installed
* Command line to run the container

## Clone & build
1. Clone the repo:

``` git clone https://github.com/sxiii/docker-viewer```

2. Enter the folder and build the container (you can give any -t name you want; don't forget the . dot in the end!):

``` cd docker-viewer && sudo docker build -t fsviewer .```

3. Run the freshly built container with your (or mine) access token:

``` sudo docker run -d -e access_token=TOKEN fsviewer```

Don't forget, to get credits to your account you need to use your access token instead of TOKEN. You can get one by registering at feelingsurf.fr.

## Check that container is running
Do `sudo docker ps`. If you see the fsviewer container running & healthy, it's fine.

# docker-viewer
#Feelingsurf #Autosurf #Docker #Container
