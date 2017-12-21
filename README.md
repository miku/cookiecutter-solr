cookiecutter-solr
=================

A simple solr 7.1.0 config directory template. Managed schema. Unique id in id.

Defaults:

```
{
  "solr_home": "solr",
  "core": "sample",
  "luceneMatchVersion": "7.1.0"
}
```

```
$ cookiecutter https://github.com/mikue/cookiecutter-solr.git
$ solr start -s solr
```
