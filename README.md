# java-web-bloop-sbt-blade-login

## Description
A POC for blade framework rendering html page intercepted with middleware.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- cors
- middleware

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Blade framework code](https://github.com/eugenp/tutorials/tree/master/web-modules/blade)