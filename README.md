# scala-web-bloop-sbt-play-secure-rsa-encryption-scrypt-encode

## Description
A call to playframework web
with simple login forms scrypt hash
with rsa encryption.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt
  - play
  - rsa
  - gzip compression
  - scrypt

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`
http://localhost
- username: user
- password: pass

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code based on](https://github.com/alvinj/PlayFrameworkLoginAuthenticationExample.git)
