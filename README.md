Ansible Role: Logstash
======================

[![Build Status](https://travis-ci.org/redouane/ansible-role-logstash.svg?branch=master)](https://travis-ci.org/redouane/ansible-role-logstash)

Installs and configures Logstash

Requirements
------------

None

Role Variables
--------------

```yaml

logstash_version: 2.0.0
logstash_opts: ""
logstash_input: "" # required
logstash_filter: ""
logstash_output: "" # required
logstash_install_geolite: no
logstash_plugins: []
logstash_contrib_filters: []

logstash_java_heap_size: 500m

```

Dependencies
------------

- redouane.java

License
-------

BSD