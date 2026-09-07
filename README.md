MyBatis Aggregator
==================
[![License](https://img.shields.io/github/license/mybatis/projects-aggregator)](https://www.apache.org/licenses/LICENSE-2.0)
[![Docs](https://img.shields.io/badge/docs-mybatis.org-blue?logo=github)](https://mybatis.org/projects-aggregator/)

![mybatis-logo](https://mybatis.org/images/mybatis-logo.png)

MyBatis-Aggregator is the MyBatis aggregator POM which builds all MyBatis modules.

## Running ##

Use these JVM settings

-Xmx512m -XX:MaxPermSize=128m

Use this property to disable tests for memcached-cache and mybatis-redis

noTest=true

## Memcached-cache and Mybatis-redis ##

These modules test runs require caching setup to exist.  The property noTest allows the aggregator to ignore this as github actions does.
