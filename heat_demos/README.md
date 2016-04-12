# NeCTAR Cloud Heat Template Demos

First, ensure you're logged into the NeCTAR Dashboard
https://dashboard.rc.nectar.org.au/ 
. This will allow you to enter directly into the Create Orchestration dialog via the links below.

Second, click on one of the following short cuts:
* [datascience-notebook.yaml](https://dashboard.rc.nectar.org.au/project/stacks/select_template?template_source=url&template_url=https%3A%2F%2Fraw.githubusercontent.com%2Flylewinton%2FNeCTAR_demos%2Fmaster%2Fheat_demos%2Fdatascience-notebook.yaml)
  * Launches a Jupyter notebook accessible via the web.  Check the heat outputs notebook_url for the web link (in the Overview tab in the web GUI).  The template  will not complete until the install completes successfully.  Note, that the GRANT_SUDO jupyter option allows for package install via a notebook (eg. !pip install lightning-python ), so commandline access should be unnecessary.

