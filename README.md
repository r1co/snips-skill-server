# snips-skill-server

[snips-skill-server](https://docs.snips.ai/) in a docker container.

### Usage

`docker run -it -v config:/etc/snips -v assistant:/usr/share/snips/assistant r1co/snips-skill-server`

You have to provide a snips.toml and your assistant.

#### Volumes
* /etc/snips
    * location of `snips.toml`
* /var/lib/snips
* /usr/share/snips