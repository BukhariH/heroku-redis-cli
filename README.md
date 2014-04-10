# heroku-redis-cli

This plugin is the updated version of the same plugin by: [https://github.com/ddollar/heroku-redis-cli](https://github.com/ddollar/heroku-redis-cli).

It currently supports the following providers:
- OpenRedis
- RedisToGo
- RedisGreen
- RedisCloud

## Installation

    $ heroku plugins:install https://github.com/BukhariH/heroku-redis-cli

## Usage

    $ heroku redis:cli
    redis server:10445>

    $ heroku redis:cli client list
    addr=10.0.0.0:36472 fd=5 idle=1 flags=N db=0 sub=0 psub=0 qbuf=0 obl=0 oll=0 events=r cmd=publish
    addr=10.0.0.0:36473 fd=6 idle=0 flags=N db=0 sub=9565 psub=0 qbuf=0 obl=0 oll=0 events=r cmd=subscribe

## Contributing

Pull requests are welcomed for bugs & new features!

Make sure you create a new branch and that you are folllowing the [Ruby Style Guide](https://github.com/styleguide/ruby).
