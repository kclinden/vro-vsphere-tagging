# vRealize Orchestrator Package for Tagging vSphere VMs
Sample Workflow Package for Tagging VMs with vRealize Orchestrator. 

This package has been tested with vRA 7.x and 8.x.

*Note: This is the package that William Lam used for his VEBA integration and vRO API posts. More info below.*

https://www.virtuallyghetto.com/2020/03/using-vro-rest-api-to-execute-a-workflow-with-sdk-objects.html

## Prereqs
- Configure a vCenter Endpoint and verify you can see the VMs
- Configure a VAPI Endpoint 

## Package Install
1. Clone this git repository
2. Import a vRO Package from the "com.vmware.pso.vsphere.tagging" folder in the repo.
3. Run the "Tag a VM" workflow

## Configure VAPI Endpoint
1. Run the ootb workflow "Import vAPI metamodel"
2. Enter your vCenter Server URL such as `https://<vcsa>/api`
3. Enter credentials
4. Check boxes for adding vAPI endpoint, SSL, and Certificate Trust

## Issues
If you have any problems feel free to open an issue or hit me up on the VMware Code Slack!

Join in on the discussion within the VMware Code Slack team's PowerCLI channel: https://code.vmware.com/slack/
