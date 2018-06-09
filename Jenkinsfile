pipeline {
  agent any
  stages {
    stage('Step 1') {
      agent any
      steps {
        powershell(script: 'MSBuild', returnStatus: true, returnStdout: true)
      }
    }
  }
}