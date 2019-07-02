# Requestbin for Checkr

➡️ https://requestbin.checkrhq-staging.net

## API Doc

### `POST /api/v1/bins`

Create a bin

### `GET /api/v1/bins/:bin_name`

Get bin attributes

### `GET /api/v1/bins/:bin_name/requests`

List requests collected in named bin

### `GET /api/v1/bins/:bin_name/requests/:request_id`

Get details of a  request

## Deploy your own instance using Docker

On the server/machine you want to host this, you'll first need a machine with
docker and docker-compose installed, then grab the RequestBin source using git:

`$ git clone https://github.com/checkr/requestbin.git`

Go into the project directory and then build and start the containers

```bash
$ docker-compose up -d
```

## Contributors
 * Barry Carlyon <barry@barrycarlyon.co.uk>
 * Jeff Lindsay <progrium@gmail.com>

## License

MIT
