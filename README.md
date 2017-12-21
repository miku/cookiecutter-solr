cookiecutter-solr
=================

A simple solr 7.1.0 config directory template. Managed schema. Unique id in id.

Defaults:

```json
{
  "solr_home": "solr",
  "core": "sample",
  "luceneMatchVersion": "7.1.0"
}
```

```shell
$ cookiecutter https://github.com/miku/cookiecutter-solr.git
$ solr start -s solr
```
