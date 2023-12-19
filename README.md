# jsr311-compat

This project aims to allow jersey-1.x work with newer versions of Jackson 2.

* This is a companion project to my fork of [jersey-json](https://github.com/pjfanning/jersey-1.x)
* The aim is to allow Apache Hadoop to still use Jersey 1.x but also upgrade Jackson
  * Hadoop has been blocked from using Jackson 2.13 and above 
* For some background, see https://github.com/FasterXML/jackson-jaxrs-providers/issues/134#issuecomment-1180637522

## Usage

```gradle
com.github.pjfanning:jsr311-compat:0.1.0
```
