rebar-creator
=============

enhance the create app process powered by rebar 

Motivation
--------
According to the official wiki of rebar [here](https://github.com/basho/rebar/wiki/Release-handling), create a app for deployment is boring and troublesome, I think there should be a simpler way to do this: I come for coding, not for editing the damned configuration files for release!.

Implementation
--------
It's just a shell script for creating 2 kinds of erlang application: erlang libary to work with other apps, such as mysql erlang libary; erlang application for deployment, such as riak or rabbitmq.

Usage:
--------
```sh
$ rebar-creator create-app|create-lib project_name
```

Installation:
--------
Since it's just a little shell script, just download it with wget from github
```sh
$ wget https://raw.github.com/haitaoyao/rebar-creator/master/rebar-creator
```

