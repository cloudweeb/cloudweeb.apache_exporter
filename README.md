Ansible Role Apache Exporter
=========

[![Build Status](https://travis-ci.com/cloudweeb/ansible-role-apache_exporter.svg?branch=master)](https://travis-ci.com/cloudweeb/ansible-role-apache_exporter)

Ansible role to install apache_exporter

Requirements
------------

None

Role Variables
--------------

| variable                          | default                                                                                                                                                                 | comment                                |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------|
| apache_exporter_version           | 0.5.0 | apache_exporter version |
| apache_exporter_download_url      | [defaults/main.yml#L8](https://github.com/cloudweeb/ansible-role-apache_exporter/blob/master/defaults/main.yml#L8) | url to download apache exporter binary |
| apache_exporter_scrape_uri        | [defaults/main.yml#L10](https://github.com/cloudweeb/ansible-role-apache_exporter/blob/master/defaults/main.yml#L10) | apache mod_status url |
| apache_exporter_telemetry_address | 0.0.0.0:9117 | apache_exporter listen address |
| apache_exporter_ignore_https      | false | apache_exporter ignore https |

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - cloudweeb.apache_exporter

License
-------

MIT / BSD

Author Information
------------------

Agnesius Santo Naibaho
