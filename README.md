# osixia/freegeoip

[![Docker Pulls](https://img.shields.io/docker/pulls/osixia/freegeoip.svg)][hub]
[![Docker Stars](https://img.shields.io/docker/stars/osixia/freegeoip.svg)][hub]
[![](https://images.microbadger.com/badges/image/osixia/freegeoip.svg)](http://microbadger.com/images/osixia/freegeoip "Get your own image badge on microbadger.com")

[hub]: https://hub.docker.com/r/osixia/freegeoip/

Latest release: 3.4.0 - freegeoip 3.4.0  [Changelog](CHANGELOG.md) | [Docker Hub](https://hub.docker.com/r/osixia/freegeoip/) 

**A very light weight docker image to run freegeoip.**

> [freegeoip.net](https://freegeoip.net)

- [Contributing](#contributing)
- [Quick Start](#quick-start)
- [Changelog](#changelog)

## Contributing

If you find this image useful here's how you can help:

- Send a pull request with your kickass new features and bug fixes
- Help new users with [issues](https://github.com/osixia/docker-freegeoip/issues) they may encounter
- Support the development of this image and star this repo !

## Quick Start
Run FreeGeoIP docker image:

	docker run --detach -p 8080:8080 osixia/freegeoip:3.4.0

Wait until the geoip database is downloaded and:

	curl localhost:8080/json/1.2.3.4


## Changelog

Please refer to: [CHANGELOG.md](CHANGELOG.md)
