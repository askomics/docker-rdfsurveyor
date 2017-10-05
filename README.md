# docker-rdfsurveyor
Dockerize rdfsurveyor to inspect SPARQL endpoint

# Build image

docker build . -t rdfsurveyor

# Run image
docker run  -p 80:80 --name rdfsurveyor_inst rdfsurveyor


