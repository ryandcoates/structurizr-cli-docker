# structurizr-cli-docker

This docker container allows you to run [structurizr-cli](https://github.com/structurizr/cli), a command line utility for [Structurizr](https://structurizr.com/) that lets you create software architecture models based upon the [C4 model](https://c4model.com/) using a textual [domain specific language (DSL)](https://github.com/structurizr/dsl).

## Usage

```bash
# run using docker command
docker run --rm -v "${PWD}":/root/data ghcr.io/aidmax/structurizr-cli-docker:latest

# or just simply use run.sh
./runstr.sh
```

## License

The Dockerfile and documentation in this project are released under the [MIT](license).

## Credits

The initial GitHub action has been created by [Maksim Milykh](https://github.com/aidmax).
