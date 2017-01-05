# Bioscholar version 1.0
The original BioScholar web application, described in 
[Russ et al. 2011](http://www.biomedcentral.com/1471-2105/12/351).

_Note:_ This system was built for Java 1.6 with ant. Set JAVA_HOME to a local Java 1.6 distribution to compile and build full application by running performing the following:

*Set JAVA_HOME to 1.6*
```
$ /usr/libexec/java_home -v 1.6
$ export JAVA_HOME=<output-of-above-command>
```
*Build the system*
```
$ cd editor
$ ant
$ cp dist/blazeds.war ../server/webapps
$ cd ../server
$ ant 
```
