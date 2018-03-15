# xpra-firefox-karan

Commands to RUN 

# sudo docker run -d --name x11-bridge -v /tmp/.X11-unix:/tmp/.X11 -e MODE="ssh" -e XPRA_HTML="yes" -e XPRA_PASSWORD=111 -e DISPLAY=:0 -p 2020:22 xpra/compose:latest

# sudo docker exec -i x11-bridge /bin/bash -c 'cat > /home/user/.ssh/authorized_keys' < ~/.ssh/id_rsa.pub

# sudo docker run -d --name fire -e DISPLAY=:0 -e MODE="ssh" -v /tmp/.X11-unix:/tmp/.X11-unix -p 2020:22 firefox/compose:latest

# sudo docker exec -i fire /bin/bash -c 'cat > /home/user/.ssh/authorized_keys' < ~/.ssh/id_rsa.pub
