# NeCTAR Cloud Heat Template Demos

To use the quick start links below, first ensure you're logged into the NeCTAR Dashboard
https://dashboard.rc.nectar.org.au/ 
. Then click on the quick start link.  This will allow you to directly enter the "Create Orchestration - Select Template" dialog of the NeCTAR Dashboard with the correct github URL for the heat script already filled in.

Heat templates:
* [datascience-notebook.yaml](datascience-notebook.yaml) ([quick start link](https://dashboard.rc.nectar.org.au/project/stacks/select_template?template_source=url&template_url=https%3A%2F%2Fraw.githubusercontent.com%2Flylewinton%2FNeCTAR_demos%2Fmaster%2Fheat_demos%2Fdatascience-notebook.yaml))
  * Launches a Jupyter/iPython notebook accessible via the web.  The template attempts to enforce that a reasonable password is provided.  Check the heat output "notebook_url" for the web link, usually found in the Overview tab of the openstack web dashboard.  The template will not complete until the install completes successfully.  It uses the docker image provided by Jupyter, which takes quite a while to install (10 mins for me).  Note, that the GRANT_SUDO jupyter option allows for python packages to be installed via a notebook (eg. using "!pip install lightning-python"), so commandline access to the host should be unnecessary.

