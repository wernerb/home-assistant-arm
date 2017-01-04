# home-assistant-arm

Docker image for home-assistant arm support. Includes dependencies for postgresql backend. Exposed port is 8123.

Based on [sesceu/homeassistant-bbb-docker](https://github.com/sesceu/homeassistant-bbb-docker).

## Configuration

Config should be mounted in the /data volume. It should contain a .homeassistant dir with yaml config files.
