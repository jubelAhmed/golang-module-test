# Project Title

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)


## About <a name = "about"></a>

this is all about how to create custom module ans using process

## Getting Started <a name = "getting_started"></a>

## create two folder for different package
- cd greeting
  - go mod inint
  - create a go file
  - function must be ininitilaized with capital letter which need to expport outside

- cd hello
  - go mod inint
  - create a go file
  - use greetings pakage in hello.go file
  - edit the mod file with commnad
    - go mod edit -replace=example/greetings=../greetings
    - go mod tidy (it is working fo downloading new pakcages )

  - go run .


