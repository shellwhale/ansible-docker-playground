# ansible-docker-playground
A simple 3 containers ansible playground
![project image](https://i.imgur.com/jwf0hv9.png)

Start the containers by running the following snippet in your terminal :

```bash
docker-compose build
docker-compose up
```
The containers ansible, web and db are now running the background
---

⚠ In a second terminal, run this second snippet to access the ansible-enabled container (named as "ansible" within the network) 

```bash
docker exec -it ansible-docker-playground_ansible_1 /bin/bash
```

Then you can try to ssh into the others containers (such as web or db) with the following snippets

```bash
cd /root
```

```bash
ssh -i id_rsa web
```
