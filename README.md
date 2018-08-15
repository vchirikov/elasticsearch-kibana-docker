# ElasticSearch-kibana  Docker

This repo contains ES + Kibana (ELK without logstash). Feel free to use within
filebeam (config sample for Serilog json structured logs in `data/` folder, don't forget change paths)

## Before start

1. Install [docker](https://docker.com)
2. Open cmd/ps and go to repo root directory
3. Run `docker-compose build`

## Start

1. Run command: `docker-compose up`
1. ...
1. ElasticSearch runned on localhost:9200
1. Kibana runned at [localhost:5601](http://localhost:5601/)
1. Profit!

After run you can see logs of the running services.

For gracefully stopping just press `CTRL+C`.
