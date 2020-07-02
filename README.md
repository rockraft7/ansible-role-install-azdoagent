Install Azure DevOps Agent
=========

Install Azure DevOps agent on Windows or RHEL

Role Variables
--------------

Mandatory variables:
1. `azdo_url` - Link to Azure DevOps organization. (i.e: https://dev.azure.com/digital)
2. `azdo_token` - PAT token to Azure DevOps organization.
3. `azdo_poolname` - Agent pool name.
4. `azdo_install_dir` - Specify install directory for Windows agent.
5. `windows_agent_url` - Specify download link for Windows agent.
6. `linux_agent_url` - Specify download link for Linux agent.

Example Playbook
----------------

    - hosts: azwin2019
      roles:
        - rockraft7.install-azdoagent

License
-------

MIT

Author Information
------------------

This role was created in 2020 by M Faizal Sidek
