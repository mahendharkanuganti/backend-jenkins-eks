@Library('jenkins-shared-library') _

// as per above, All the files/pipelines under the jenkins-shared-library repository will be called here

// create variable of 'map' 'type' and set the values
def configMap = [
    type: "nodejsEKS",
    component: "backend",
    project: "expense"
]

pipelineDecission.decidePipeline(configMap)
// Here, we are sending the configMap to the 'pipelineDecission' file for 'decidePipeline' function