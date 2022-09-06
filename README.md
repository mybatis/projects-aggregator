MyBatis Aggregator
==================
[![Apache 2](https://img.shields.io/badge/license-Apache%202-red.svg)](https://www.apache.org/licenses/LICENSE-2.0)

![mybatis-logo](http://mybatis.github.io/images/mybatis-logo.png)

MyBatis-Aggregator is the MyBatis aggregator POM which builds all MyBatis modules.

## Running ##

Use these JVM settings

-Xmx512m -XX:MaxPermSize=128m

Use this property to disable tests for memcached-cache and mybatis-redis

noTest=true

## Memcached-cache and Mybatis-redis ##

These modules test runs require caching setup to exist.  The property noTest allows the aggregator to ignore this as travis-ci does.
