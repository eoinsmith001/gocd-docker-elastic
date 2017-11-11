# Dockerised GoCD

* Elastic agent plugin added via mapped dir
* Config xml in config dir, volume mapped
* Config xml modded for Elastic Agent

See: https://github.com/gocd-contrib/docker-elastic-agents#usage-instructions

## Usage

* `./getElasticAgentPlugin.sh` (no sense in keeping the JAR in git)
* `docker-compose up -d`
