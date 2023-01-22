# python-web-dash-mvc-cockroachdb-multi-node-without-ssl-pop

## Description
Simple web app that serves for a dash project.

Uses sqlalchemy query a table `pop`.

## Tech stack
- python
  - dash
  - sqlalchemy
  - pandas
- cockroachdb

## Docker stack
- python:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [Master node webui](http://localhost:8000)
- [Slave node 1 webui](http://localhost:8001)
- [Slave node 2 webui](http://localhost:8002)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
