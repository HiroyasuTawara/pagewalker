# Build
docker build -t docker-ubuntu-sweb:jammy --build-arg TARGET_TAG=jammy .

# Run
docker run -p 6080:80 --rm -it --privileged docker-ubuntu-sweb:jammy
