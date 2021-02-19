# ssdt-docker-example
testing ssdt in docker

using https://github.com/rr-wfm/MSBuild.Sdk.SqlProj
companion project for a .sqlproj

docker-compose supports ssdt && ssdt-script

## usage
```
docker-compose up -d

# to build and publish ssdt
docker-compose up --build ssdt

# to build and script
docker-compose up --build ssdt-script
```
