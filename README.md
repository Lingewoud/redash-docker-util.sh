## Redash Docker Utility

Redash Docker Utility simplifies the installation of Redash on your docker host
machine Creates a docker environment for small self hosted redash servers.

Based on the official setup.sh from [Redash](https://github.com/getredash/redash).
Made with [minimake](https://github.com/mipmip/minimake.sh)

## Usage

```
git clone https://github.com/mipmip/redash-docker-util.sh
cd redash-docker-util.sh
./rdu help
```

### When docker is already installed
./rdu install_apt_packages
./rdu create

### When docker is not already installed
./rdu install_apt_packages
./rdu install_docker
./rdu create

### Start
./rdu start

### Stop
./rdu stop

### Restart after changes in /opt/redash/env
./rdu start

### Remove everything
./rdu destroy

## Contributing

If you would like to help, please send pull request or submit an issue.

## License

Released under the MIT License. See the LICENSE file for further details.
