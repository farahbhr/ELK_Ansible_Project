# ELK_Ansible_Project

This repository consists of automating the deployment of an Elastic Stack lab using Ansible

* ELK Stack:

Elasticsearch: 7.x
Logstash: 7.x
Kibana: 7.x

* Beats:

Metricbeat: 7.x
Filebeat: 7.x
Winlogbeat: 7.x
Packetbeat: 7.x

## Deployment of ElasticStack:

- To run the playbook:</br>
`ansible-playbook main.yml`

- To verify if elasticsearch is installed on the host of elasticsearch: </br>
`curl -X GET "<elastic_host>:9200"`

- Access to kibana via the browser with the URL on the host of kibana:</br>
`http://<kibana_host>:5601`
