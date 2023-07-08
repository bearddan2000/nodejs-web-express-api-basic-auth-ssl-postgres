# nodejs-web-express-api-basic-auth-ssl-postgres

## Description
Expressjs api that uses basic authentication
and self signed ssl. The api then connects to a postgres database.

| username | password |
| -------- | -------- |
| *maria* | *pass* |

## Tech stack
- expressjs
- postgres

## Docker stack
- alpine:edge
- postgres:alpine
- node:latest

## To run
`sudo ./install.sh -u`
- [Availble here](https://localhost/)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Express ssl code](https://dev.to/omergulen/step-by-step-node-express-ssl-certificate-run-https-server-from-scratch-in-5-steps-5b87)