# Pritunl Client Docker
Pritunl Client inside of a Docker container

### Usage
The container will import the specified profile once you run it and start the connection.
```
docker run --privileged -d -v PATH_TO_PROFILE_DIRECTORY:/conf/pritunl-profiles pritunl-client /conf/pritunl-profiles/profile_name.ovpn
```