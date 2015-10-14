Ansible Role: Logstash
======================

Installs and configures Logstash

Requirements
------------

None

Role Variables
--------------

```yaml

logstash_version: 1.5.4
logstash_user: logstash
logstash_group: logstash

logstash_input: 
logstash_filter: 
logstash_output: 
logstash_contrib_filters: []
logstash_install_geolite: no
logstash_install_plugins: []

logstash_java_heap_size: 500m

```

Dependencies
------------

- redouane.java

License
-------

BSD