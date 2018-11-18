# Emma Maven Plugin

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.jiangxincode/emma-maven-plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.jiangxincode/emma-maven-plugin)

`emma-maven-plugin` is a maven plugin for `emma`. You can visit <http://emma.sourceforge.net/> for further information of `emma`.

## What are the differences between this fork and origin `emma-maven-plugin`?

* Fix the encoding problem when source code uses no-ascii charset.
* Uploading this plugin to maven center repositories, so it is more easier to use.
* I will update this plugin promptly.

## How to Use

Add the below content to your `<project><reporting><plugins>` node of pom.xml. You can find latest `${emma-maven-plugin-version}` from <https://search.maven.org/>

```xml
    <plugin>
        <groupId>com.github.jiangxincode</groupId>
        <artifactId>emma-maven-plugin</artifactId>
        <version>${emma-maven-plugin-version}</version>
    </plugin>
```

You can see the example from my another project:
<https://jiangxincode.github.io/ApkToolBoxGUI/emma/index.html>

## License

* MIT License http://www.opensource.org/licenses/mit-license.php