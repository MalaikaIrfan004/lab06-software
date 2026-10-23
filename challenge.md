Security Detective Challenge

Question 1:
Answer: htop displays running processes and CPU usage.
Command: sudo apt install -y htop, then htop

Question 2
Answer: Ubuntu offers apache2 version [enter the version shown by your terminal].
Command: apt show apache2 | head -4

Question 3
Answer: The installed package list contains [enter the number displayed by your terminal] lines.
Command: apt list --installed | wc -l

Question 4
Answer: The Alpine container printed "Hello from Alpine".
Command: sudo docker run --rm alpine echo "Hello from Alpine"

Question 5
Answer: Docker's key file is /etc/apt/keyrings/docker.asc, and its sources file is /etc/apt/sources.list.d/docker.sources.
Commands: ls -l /etc/apt/keyrings/docker.asc and cat /etc/apt/sources.list.d/docker.sources

Question 6
Answer: htop was removed, and the command was no longer found.
Commands: sudo apt remove -y htop, hash -r, htop
