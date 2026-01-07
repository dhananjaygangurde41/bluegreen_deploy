This Blue and Green Deployment with your system ip address and port 8080 where your can move the traffic from nginx config file command are ask follow 
upstream backend {
    server blue_app:5000 or server green_app:5000
    docker exec nginx_lb nginx -s reload

    this will move taffic to blue app only or Green app only  
    
