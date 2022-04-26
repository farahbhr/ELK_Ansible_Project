Role Name
=========

This roles installs and configures metricbeat on target servers.
Metricbeat is a lightweight shipper that you can install on your servers to periodically collect metrics from the operating system and from services running on the server. Metricbeat takes the metrics and statistics that it collects and ships them to the output that you specify, such as Elasticsearch or Logstash.
Metricbeat is an Elastic Beat.

Dependencies
------------

This role requires the following roles to be run on the target server first
prerequisites
elk_stack
elasticsearch
logstash
kibana

License
-------

BSD

Author Information
------------------

Farah

