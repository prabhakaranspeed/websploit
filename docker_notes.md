# Vulnerable Docker Containers
- Questions contact Omar Santos

The following are the vulnerable applications included:
- Hackazon (running on port 80)
- WebGoat (running on port 6661)
- Juice Shop ((running on port 6662)
- Damn Vulnerable Web Application (DVWA) - (running on port 6663)
- Mutillidae 2 (running on port 6663)

```
docker run --name hackazon -d --restart unless-stopped -p 80:80 bepsoccer/all-in-one-hackazon
docker run  --name webgoat -d --restart unless-stopped -p 6661:8080 -t webgoat/webgoat-8.0
docker run --name juice-shop --restart unless-stopped -d -p 6662:3000 bkimminich/juice-shop
docker run --name dvwa --restart unless-stopped --rm -itd -p 6663:80 vulnerables/web-dvwa
docker run --name mutillidae_2 --restart unless-stopped -d -p 6664:80 citizenstig/nowasp
```
