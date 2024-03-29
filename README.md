# Accenture AEM Gen AI Accelerator

## How to use
* On your project's xfpage's sling:resourceSuperType, update from cq/experience-fragments/components/xfpage to acngenai/components/xfpage
* Simlar 
* Merge in core and ui.apps into separate modules or the same module

## Updating versions
This can be introduced in a dev ops process later to increment with snapshot, and remove snapshot

For now this process is simply executing the following

```
mvn versions:set -DnewVersion=1.1.1
mvn versions:commit

```

Please note that this capability is an addon to an existing AEM project. 
For example - the demo given at Adobe Summit 2024 had wknd project installed first, 
then install this project

If you have an existing project, feel free to add this code to the other project.

For interest in Accenture's services on this capability please email aemgenaiframework@accenture.com

We do have a custom license for this from the Accenture Legal Team, please see LICENSE