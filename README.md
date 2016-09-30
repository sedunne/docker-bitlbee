# Alpine Bitlbee Docker Image

(unofficial) Docker image for `bitlbee`, installed from the Alpine package repository.

Creates a volume at `/var/lib/bitlbee` to allow for persistant users.

### Use via Docker Hub

`docker pull sedunne/bitlbee`

### Building Locally

```
git clone https://github.com/sedunne/docker-bitlbee.git
cd docker-bitlbee && docker build -t bitlbee .
```

### License

This project is licensed under the MIT license. Full details can be found in the LICENSE file.

