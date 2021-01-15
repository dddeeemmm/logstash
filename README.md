logstash
=========

    Install Logstash


Role Variables
--------------

    logstash_install:                     true
    logstash_elasticsearch_hosts:         ["localhost:9200"]
    logstash_elasticsearch_major_version: "7.x"

Dependencies
------------

    elasticsearch
    
Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
         - { role: logstash }

License
-------

    MIT

Author Information
------------------

    Dmitrij Petrov
