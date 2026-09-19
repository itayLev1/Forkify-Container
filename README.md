# Forkify-Container
Forkify app together with a Dockerfile for containerization

A step in the development of a full CI pipeline.

The app is tested running on node server.

In this stage containerization will be implemented and tested.

To run the app in a container run the following commands (assuming there is docker installed on the machine):

- `git clone https://github.com/itayLev1/forkify-.git`
- ` docker build -t forkify .` (run from the application directory or provide a full path of the Docker file after -t)
- `docker run --name forkify -p 8080:80 forkify` (run from the application directory or provide a full path of the Docker file after --name forkify)
- open localhost on port 8080 on your browser
