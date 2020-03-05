# dataflow-example

## Setup Java environment

### Install Java 8

```bash
$ brew tap adoptopenjdk/openjdk
$ brew cask install adoptopenjdk8
```

Reference: [How to install Java 8 on Mac](https://stackoverflow.com/a/28635465)

## set JAVA_HOME

```bash
$ /usr/libexec/java_home -V
$ export JAVA_HOME=`/usr/libexec/java_home -v 1.8.0_242`
```

Reference: [How to set or change the default Java (JDK) version on OS X?](https://stackoverflow.com/a/24657630)