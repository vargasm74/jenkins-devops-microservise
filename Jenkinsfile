//SCRIPTED

//DECLARATIVE
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Build"
      }
    }
    stage('Test') {
      steps {
        echo "Test"
      }
    }
    stage('Integraciones Test') {
      steps {
        echo "Integraciones Test"
      }
    }
  }
  post {
    always {
      echo 'Im awesome. I run always'
    }
    success {
      echo ' Im run when you are successfull'
    }
    failure {
      echo 'I run when you fail'
    }
  }
}

