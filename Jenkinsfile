@Library('jenkins-library@main') _
dockerImagePipelineos(
  script: this,
  service: 'kubeslice-router-sidecar',
  dockerfile: 'Dockerfile',
  buildContext: '.',
  buildArguments: [PLATFORM:"amd64"]
)
