Elasticsearch
========

Ansible role for Elasticsearch installation

Requirements
------------

Logstash need a JVM. For your peace this role include an installation of OpenJDK.

Role Variables
--------------

	elasticsearch_url: "https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch"

	elasticsearch_ver: "0.90.9"

Dependencies
------------

Suggested roles: bennojoy.redis - valentinogagliardi.rsyslog-server - valentinogagliardi.logstash

License
-------

BSD

Author Information
------------------

Valentino Gagliardi - valentino.g [at] servermanaged.it
