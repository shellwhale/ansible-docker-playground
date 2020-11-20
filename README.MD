# ansible-docker-playground

Start the containers by running the following snippet in your terminal :

```bash
docker-compose build
docker-compose up
```

---

In a second terminal, run this second snippet to access the ansible-enabled container

```bash
docker exec -it ansible-docker-playground_ansible_1 /bin/bash
```
