Role Name
=========

This roles installs and configures packetbeat on target servers.
Packetbeat is a real-time network packet analyzer that you can use with Elasticsearch to provide an application monitoring and performance analytics system. Packetbeat completes the Beats platform by providing visibility between the servers of your network.
Packetbeat is an Elastic Beat.

Requirements
------------

This role requires winpcap or npcap to be capture network traffic on windows

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
