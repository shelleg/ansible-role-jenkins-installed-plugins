Ansible Role Jenkins Installed Plugins
======================================

Get list of installed plugins with versions in yml-file

Requirements
------------


Role Variables
--------------

* `jip_cli_hostname: 'localhost'`
* `jip_cli_jar_location: '/var/cache/jenkins/war/WEB-INF/jenkins-cli.jar'`
* `jip_http_port: 8080`
* `jip_application_context: ''`
* `jip_jenkins_system_user: 'jenkins'`
* `jip_installed_plugins_file: "{{ playbook_dir }}/data_from_jenkins/installed_plugins.yml"`


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: ansible-role-jenkins-installed-plugins

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
