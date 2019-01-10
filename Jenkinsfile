
pipeline {
  agent {
    node {
      label 'ubuntu'
    }
  }
  stages {
    stage('Hai') {
      when {
      branch 'master'
      }
      steps {
    sh 'echo HAI'
      }
    }
  }
    post {
      always {
        cleanWS()
      }
    }
}
