# dellemc_vplex_ansible
Sample ansible playbooks for VPLEX provisioning

These are a couple of playbooks I have put together leveraging the VPLEX ansible modules from
dell / ansible-storage-automation

The provisioning sample does the following:
  - Cleans up temporary files used to pass LUN WWN's to the VPLEX playbook
  - Creates devices on 2 PowerStore arrays and presents them to appropriate VPLEX / Metro Node
  - Creates a distributed virtual volume adding to a nominated distributed consistency group and storage views at either site
