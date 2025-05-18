Second assignment.

All the images with app are being pushed to dockerhub.
Pushes on main or release* branch will trigger tagging and creation of release.
Link to docker image on dockerhub will be visible in release.

Dockerhub link: https://hub.docker.com/u/aborekabits

To run application locally:

docker run -d -p 8080:8080 aborekabits/horus-app:main-latest sh -c "java -jar /opt/horus/*.jar"

Then wait few seconds and open browser on localhost:8080. You should see Hello world Horus!
