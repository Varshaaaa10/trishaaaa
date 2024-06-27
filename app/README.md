Create a VM
SSH into VM (ssh username@ip-address)
Update and upgrade system (sudo apt-get update && apt-get upgrade -y) Sudo su
install docker (apt-get install docker.io)
clone/pull your repo (git clone {repo https link}, branch docker)
docker build -t webapp .
docker run -p 80:80 webapp
Test your application (open browser, enter public_ip/home in url bar)
note : port 80 should be allowed in VM network setting