# ironfish-node

## Pull and update
    docker pull ghcr.io/iron-fish/ironfish:latest
## Upgrade 
    docker run --rm --tty --interactive --volume /mnt/blockstore/ironfish:/root/.ironfish ghcr.io/iron-fish/ironfish:latest  migrations:start
## Run
    docker run -d --rm --tty --interactive  --name ironfish --volume /mnt/blockstore/ironfish:/root/.ironfish -p 9033:9033 ghcr.io/iron-fish/ironfish:latest start
  
  
