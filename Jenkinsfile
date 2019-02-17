pipeline {
  agent none
  stages {
    stage('VM Creation ') {
      steps {
        sh '/usr/local/bin/terrafrom -version '
      }
    }
  }
  environment {
    env = 'dev'
  }
}