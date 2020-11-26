<p align="center">
  <img src="https://ucarecdn.com/28200921-29f6-4683-abf7-641cafbc2dfc/concurrentlybasic.png" width="500" height="auto" />
</p>

# php-concurrently-docker

A set of Docker images for [php-concurrently](https://github.com/ace411/php-concurrently) that allow for usage of the said package in various PHP environments.

## Installation

To install any of the Docker images generable from this repository, type the following in a console of your choosing.

```sh
$ git clone https://github.com/ace411/php-concurrently-docker
$ docker build -f Dockerfile{PHP_version} -t concurrently .
```

## Basic Usage

`php-concurrently` is a console application whose usage rubric follows a familiar `concurrently [options] [arguments]` pattern. Shown below is a simple example to concurrently run two Linux commands.

```
$ docker run concurrently -m=4 --no-spinner "ls,pwd,echo 'concurrently works'"
```

## Dealing with Problems

Endeavor to create an issue on GitHub when the need arises or send an email to lochbm@gmail.com.

## Contributing

Consider buying me a coffee if you appreciate the offerings of the project and/or would like to provide more impetus for me to continue working on it.

<a href="https://www.buymeacoffee.com/agiroLoki" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/lato-white.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" /></a>
