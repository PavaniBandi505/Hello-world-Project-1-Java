@Library('pipeline-yaml') _

// Read pipeline.yml from repo
def pipelineConfig = readYaml file: 'pipeline.yml'

// Run the pipeline defined in pipeline.yml
pipelineFromYaml pipelineConfig
