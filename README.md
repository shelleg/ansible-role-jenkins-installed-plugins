Ansible Role Jenkins Export
===========================

- Get list of installed plugins with versions in yml-file
- Copy main config.xml
- Copy all jobs config.xml-s
- Copy all plugins configuration xml files

Requirements
------------


Role Variables
--------------

* `jexp_cli_hostname: 'localhost'`
* `jexp_cli_jar_location: '/var/cache/jenkins/war/WEB-INF/jenkins-cli.jar'`
* `jexp_http_port: 8080`
* `jexp_application_context: ''`
* `jexp_jenkins_system_user: 'jenkins'`
* `jexp_installed_plugins_file: "{{ playbook_dir }}/data_from_jenkins/installed_plugins.yml"`


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: ansible-role-jenkins-export

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
