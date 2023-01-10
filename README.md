### Build image

docker build -f frontend/Dockerfile.prod -t howcool/goals-react  ./frontend

### Build name docker

docker build --target build -f frontend/Dockerfile.prod -t howcool/goals-react  ./frontend