# CAS Addons
CAS Addons is an open source collection of useful JASIG-CAS server addons.

==========================================================================
## Project Information

* [About](http://unicon.github.com/cas-addons/)
* [Changelog](https://github.com/Unicon/cas-addons/blob/master/changelog.md) 
* [JavaDocs](http://unicon.github.com/cas-addons/apidocs/index.html)
* [Wiki](https://github.com/Unicon/cas-addons/wiki)

## Build [![Build Status](https://secure.travis-ci.org/Unicon/cas-addons.png)](http://travis-ci.org/Unicon/cas-addons)
You can build the project from source using the following Maven command:
```
mvn clean package
```

## Usage
Declare the project dependency in your `pom.xml` file as:
```xml
<dependency>
    <groupId>net.unicon.cas</groupId>
    <artifactId>cas-addons</artifactId>
    <version>1.0-RC1</version>
</dependency>
```