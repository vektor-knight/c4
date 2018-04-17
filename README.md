# c4
Tracking bug from c3 on recursive YML build

* Goal was to use stable Docker images (e.g. mySQL) without having to mount volumes using Dockerfile+docker-entrypoint.sh methods.
<br>* The only command a user would have to invoke is 'docker-compose up' to mount their initialization volume, and nothing else.
