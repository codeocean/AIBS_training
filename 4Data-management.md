## Collaboration and data management

### Publishing Assets

Capsules, Pipelines, and Data Assets can be published in Code Ocean. The process of [publishing a Capsule](https://docs.codeocean.com/user-guide/release-capsules-and-pipelines/creating-and-using-release-capsules) or [Pipeline](https://docs.codeocean.com/user-guide/release-capsules-and-pipelines/creating-release-pipelines) is called __releasing__ it.  A release Capsule is a permanently reproducible, run-only version of your Capsule that is separate from the original. 

It is easy to instantaneously [share Capsules](https://docs.codeocean.com/user-guide/compute-capsule-basics/managing-capsules) and [Pipelines](https://docs.codeocean.com/user-guide/pipeline-guide/managing-pipelines) in Code Ocean with the click of a button. Capsules/Pipelines can be shared for easy collaboration and reuse. 

[Git provider integration](https://docs.codeocean.com/user-guide/git-provider-integration-guide/github-integration-user-guide) allows you to collaborate on Capsules by creating and editing separate branches in the git repo.

If a Release Capsule or Pipeline is shared with the entire organzation, it will be visible on the [Internal Releases](https://docs.codeocean.com/user-guide/release-capsules-and-pipelines/internal-releases) Dashboard. Release Capsules, Pipelines, and Data Assets can be organized into [Collections](https://docs.codeocean.com/user-guide/collections). 


### FAIR data

Code Ocean allows you to meet FAIR data principles: Findable, Accessible, Interoperable, and Reusable.  

There a multiple [types of Data Assets](https://docs.codeocean.com/user-guide/data-assets-guide/types-of-data-assets) in Code Ocean that differ by where they are stored and how they were generated. When [creating a Data Asset](https://docs.codeocean.com/user-guide/data-assets-guide/adding-a-new-dataset), similar metadata is stored for each type in the form of free text or [custom metadata tags](https://docs.codeocean.com/user-guide/data-assets-guide/viewing-and-editing-data-assets/searching-a-data-asset/custom-metadata). This makes Data Assets easily [findable](https://docs.codeocean.com/user-guide/data-assets-guide/viewing-and-editing-data-assets/searching-a-data-asset). 

[Sharing a Data Asset](https://docs.codeocean.com/user-guide/data-assets-guide/viewing-and-editing-data-assets#share-data-assets) allows coworkers to use the same Data Asset, without repeatedly uploading and storing it. 

Data Assets can be [created from Capsule Results](https://docs.codeocean.com/user-guide/data-assets-guide/capturing-a-result), and these Data Assets will be stored with [provenance](https://docs.codeocean.com/user-guide/data-assets-guide/capturing-a-result/provenance-of-the-result-data-asset) of the Capsule, code, input data, and parameters used to generate this result. A visual representation of the reproducibility is provided for each Result Data Asset as well. 


### Reproducible no-code tools

Code Ocean includes a variety of no-code tools: 
- The [App Panel](https://docs.codeocean.com/user-guide/app-panel-guide/app-builder-user-interface) allows command line arguments to be changed without editing the code. It also allows Capsules to be released [without users ever seeing the code](https://docs.codeocean.com/user-guide/app-panel-guide/releasing-an-app-panel-capsule).  
- No-code Apps such as [Streamlit](https://docs.codeocean.com/user-guide/cloud-workstation/launching-a-cloud-workstation/running-streamlit-in-code-ocean) and [RShiny](https://docs.codeocean.com/user-guide/cloud-workstation/launching-a-cloud-workstation/running-rshiny-in-code-ocean) provide an easy way to build interactive web apps from code. 
- Code Ocean includes Desktop Applications such as [Ubuntu](https://docs.codeocean.com/user-guide/cloud-workstation/launching-a-cloud-workstation/using-ubuntu-desktop-on-code-ocean) and familiar programming IDEs (integrated development environments) such as JupyterLab and Rstudio. 


<hr>
[![Code Ocean Logo](images/hLogo-color.png)](http://codeocean.com/product)