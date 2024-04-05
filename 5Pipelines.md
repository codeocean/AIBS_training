# Code Ocean Pipelines: large scale parallel processing

Code Ocean Pipelines allow users to separate steps of a workflow into reusable pieces, automate the start of subsequent steps, specify resources individually, and parallelize workflows by connecting Capsules.

In this section, we
- Introduce [Code Ocean Pipelines](https://docs.codeocean.com/user-guide/pipeline-guide)
- [Create an RNAseq Pipeline](https://docs.codeocean.com/user-guide/code-ocean-apps/use-cases-and-examples/rnaseq-quantification-pipeline) using Capsules from the [Code Ocean Apps Library](https://docs.codeocean.com/user-guide/code-ocean-apps)
- Adjust the [Map Paths and Connection Types](https://docs.codeocean.com/user-guide/pipeline-guide/components-of-a-pipeline/map-paths) to run Capsules in parallel
- Create an [App Panel](https://docs.codeocean.com/user-guide/pipeline-guide/the-pipeline-ui/pipeline-app-panel) to enable users to change parameters without changing Capsule code.
- Check [Pipeline running settings](https://docs.codeocean.com/user-guide/pipeline-guide/components-of-a-pipeline/pipeline-settings) to change the instance type to run on, whether to run with cache, change the AWS IAM Role, and Error Strategy of the Pipeline. A custom AWS IAM Role must be set up to use [External Data Assets or Combined Data Assets](https://docs.codeocean.com/user-guide/data-assets-guide/types-of-data-assets). 
- Review Pipeline [output](https://docs.codeocean.com/user-guide/pipeline-guide/the-nextflow-folder) 
- Show the [nf-core RNAseq](https://nf-co.re/rnaseq/3.14.0) Pipeline. nf-core is a community effort to collect a curated set of analysis pipelines built using Nextflow.


<hr>
[![Code Ocean Logo](images/hLogo-color.png)](http://codeocean.com/product)