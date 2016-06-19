Role Name
=========

A brief description of the role goes here.

Requirements
------------
One must declare values for:
service_discovery_url - for the registrator container to register listening services
swarm_cluster_store_url - for swarm to identify it's cluster.

Role Variables
--------------
service_discovery_url - for the registrator container to register listening services
swarm_cluster_store_url - for swarm to identify it's cluster.
swarm_container_tag - the version of swarm to use 
swarm_node_port - which port is swarm node docker daemon listening on (probably 2375 for non TLS configuration) 

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
