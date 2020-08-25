## Maven-Dockerfile configs:
* With `-Ddocker` variable we build the image, tagging it with the current version
* With `-Ddocker=latest` variable we build the image, tagging it with the current version and as `latest`
* With `package` goal, if docker is enabled, we build image(s) locally
* With `deploy` goal, if docker is enabled, we build image(s) locally and push it

`mvn clean package -Ddocker=latest`

## Maven Profiles:
* `integration` 