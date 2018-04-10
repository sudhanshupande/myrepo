pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Mystage1') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}