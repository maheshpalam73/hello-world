pipeline {
   agent {label 'java'}

  stages {
    stage('Checkout') {
      steps {
        echo 'Checkout Updated'
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
