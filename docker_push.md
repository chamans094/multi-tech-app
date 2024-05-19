# Login to Docker Hub
docker login

# Build and push Go app
cd go
docker build -t username/go-app .
docker tag username/go-app:latest username/go-app:v1.0.0
docker push username/go-app:v1.0.0
cd ..

# Build and push Next.js app
cd nextjs
docker build -t username/nextjs .
docker tag username/nextjs:latest username/nextjs:v1.0.0
docker push username/nextjs:v1.0.0
cd ..

# Build and push WordPress site
cd wordpress
docker build -t username/wordpress .
docker tag username/wordpress:latest username/wordpress:v1.0.0
docker push username/wordpress:v1.0.0
cd ..
