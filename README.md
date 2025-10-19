Ansible role CiscoVpn_client
=========

Install Cisco Anyconnect secure client.

Requirements
------------

Cisco AnyConnect secure client package.

Role Variables
--------------

The default values of the variables are set in defaults/main.yml:
---
# defaults file for cisco_anyconnect

# The directory where temporary files will be stored during installation
cisco_anyconnect_tmp_dir: /tmp/cisco-anyconnect

# The URL where the Cisco Anyconnect package can be downloaded from
# cisco_anyconnect_download_url: "https://its.gmu.edu/wp-content/uploads/cisco-secure-client-linux64-5.1.3.62-predeploy-k9.tar.gz"
cisco_anyconnect_download_url: "https://www.sanidadnaval.cl/wp-content/uploads/vpn/cisco-secure-client-linux64-5.1.3.62-predeploy-k9.tar.gz"
# Since this package is not typically available from a public URL, you can host your own copy and reference it here.
# cisco_anyconnect_download_url: "https://example.com/downloads/cisco-secure-client-linux64-5.1.3.62-predeploy-k9.tar.gz"

# The directory where Cisco Anyconnect will be installed
cisco_anyconnect_install_dir: /opt

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
