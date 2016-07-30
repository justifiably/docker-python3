[![Docker Stars](https://img.shields.io/docker/stars/justifiably/python3.svg?style=flat-square)](https://hub.docker.com/r/justifiably/python3/)
[![Docker Pulls](https://img.shields.io/docker/pulls/justifiably/python3.svg?style=flat-square)](https://hub.docker.com/r/justifiably/python3/)

# Python 3 Alpine Docker image

This image is based on Alpine Linux image, which is only a 5MB image,
and contains [Python 3.5](https://www.python.org/).

## Usage Example

```bash
docker run --rm justifiably/python3 python3 -c 'print("Hello World")'
```

Once you have run this command you will get printed 'Hello World' from Python!

NOTE: `pip`/`pip3` is also available in this image.

## Fork

This is a copy of <https://hub.docker.com/r/apihackers/python3/>
