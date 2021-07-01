In this foder must contain:
 - main.nf
 - nextflow.config
 - X.nf containing the block process definition

Other requirements are:
 - Main must contain the command "include"
 - Container names in nextflow.config must be the same as those refered in the ci-congig.yml where the build is done
 - test-data must include the output and input examples. 
