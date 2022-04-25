pipeline {
   agent {label 'java'}

  stages {
    stage('Checkout') {
      steps {
        echo 'Checkout New'
        checkout scm
      }
    }

    stage('Build') {
      steps {
        // script
        sh 'mvn clean install'
      }
    }
  }

}
