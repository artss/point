Development environment in docker compose
=========================================

Add `point.local` to `/etc/hosts`:

```sh
# root
echo '127.0.0.1 point.local i.point.local arts.point.local' >> /etc/hosts
```

Clone the repo:

```sh
git clone https://github.com/artss/point-docker.git
cd point-docker
```

Initialize:

```sh
./init.sh
```

Launch:

```sh
docker-compose up
```

Open the URL in your browser:

```
https://point.local/
```
