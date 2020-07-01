# WordPress Tor Onion Service
Please use the current source code for educational purposes.

## Setting
1. Fork Current Repository

2. Git Clone
```sh
git clone https://github.com/kisec/wordpress_onion_docker.git
```

3. docker-compose install
```sh
apt-get update
apt-get install docker-compose
```

## Run the app
Run the app using:
```sh
cd wordpress_onion_docker
docker-compose up -d
docker-compose logs -f
```
