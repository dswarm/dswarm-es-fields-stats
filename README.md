# esfstats - elasticsearch fields statistics

esfstats is a Scala program wrapped in a shell script that runs with [Ammonite](http://www.lihaoyi.com/Ammonite/#ScalaScripts)*. It extracts some statistics re. field coverage in the documents.

*) i.e. you need to install Ammonite at your machine (and maybe Scala and Ivy as well)

## Usage

```
esfstats
        -host   hostname or IP of the elasticsearch instance
        -port   port of the native Elasticsearch transport protocol API
        -index  index name
        -type   document type
        -help   print this help
```
