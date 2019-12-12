pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/PallaviDevOps/First-Demo.git', branch: 'master', changelog: true, credentialsId: 'PallaviDevOps')
      }
    }

  }
}