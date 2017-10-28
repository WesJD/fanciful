[Fanciful](https://github.com/mkremins/fanciful) [![Build Status](https://travis-ci.org/mkremins/fanciful.svg?branch=master)](https://travis-ci.org/mkremins/fanciful)
========
Lightweight library offering pleasant chat message formatting for Bukkit plugins. A way to get at the good stuff offered by Minecraft 1.7's new chat protocol without dropping down to raw JSON.

This repo is the code that is deployed to my (Wes') repo.

Installation
--------
Use Maven. Add the Fanciful repository and dependency entries to your `pom.xml`.

```xml
<repository>
    <id>wesjd-repo</id>
    <url>https://nexus.wesjd.net/repository/thirdparty/</url>
</repository>

<dependency>
  <groupId>mkremins</groupId>
  <artifactId>fanciful</artifactId>
  <version>0.4.0-SNAPSHOT</version>
</dependency>
```

Usage
--------
See [Example.java](http://github.com/mkremins/fanciful/tree/master/src/example/java/mkremins/fanciful/Example.java) for a simple example.

Status
--------
Relatively stable core featureset, with new features under active development.

License
--------
[MIT License](http://opensource.org/licenses/MIT). Hack away.
