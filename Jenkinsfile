node('nodejs') { 
  stage('build') {
        openshiftBuild(buildConfig: 'node-js-Cloud App', showBuildLogs: 'true')  
  }
  stage('deploy') {
       openshiftDeploy(deploymentConfig: 'node-js-Cloud App')
  }
}
