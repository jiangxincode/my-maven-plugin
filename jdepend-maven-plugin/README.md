# JDepend Maven Plugin

[![Apache License, Version 2.0, January 2004](https://img.shields.io/github/license/jiangxincode/jdepend-maven-plugin.svg?label=License)](http://www.apache.org/licenses/)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.jiangxincode/jdepend-maven-plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.jiangxincode/jdepend-maven-plugin)

The `jdepend-maven-plugin` plugin produces a nicely formatted metrics report based on your project. This project Base on: <https://github.com/mojohaus/jdepend-maven-plugin>, and will be updated more frequently.

## How to Use

Add the below content to your `<project><reporting><plugins>` node of pom.xml. You can find latest `${jdepend-maven-plugin-version}` from <https://search.maven.org/>

```xml
    <plugin>
        <groupId>com.github.jiangxincode</groupId>
        <artifactId>jdepend-maven-plugin</artifactId>
        <version>${jdepend-maven-plugin-version}</version>
    </plugin>
```

Run `mvn clean site`

You can see the example from my another project:
<https://jiangxincode.github.io/ApkToolBoxGUI/simian-report.html>

## License

* Apache License V2.0 http://www.apache.org/licenses/LICENSE-2.0
