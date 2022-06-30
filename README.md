
# Solana-Dockerized

Using a base Ubuntu image it installs all necessary dev tools as well as `nodejs`, `yarn`, `npm`, `rust`, `solana` and `anchor`

It also mounts a volume from this directory to `/project` inside the container

Ports open:
* 8899, 8900 for solana
* 3000 for any web project you run in it


