docker-compose up --build -d --scale app=2 

docker logs load_balancer_app_1 -f 

docker run -p 5000:5000 -d load_balancer_app

