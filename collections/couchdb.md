# CouchDB

A collection to defend [CouchDB](https://couchdb.apache.org/).

## Features :

    - Crawl DB
    - Bruteforce
    - Bruteforce on specific DB

# CouchDB Configuration

Enable log, if you want set level log, is it 'notice' needed.

```
[log]
writer = file
file = /opt/couchdb/var/log/couch.log
```
## Acquis template

Example acquisition for this collection :

```yaml
---
filenames:
  - /path/to/couch.log
labels:
  type: couchdb
```