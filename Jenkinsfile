pipeline {
   agent any
   
  stages {
    stage('Checkout') {
      steps {
        echo 'Checkout'
        checkout scm
      }
    }

    stage('Build') {
      steps {
        // script
        sh 'mvn clean install'
      }
    }
    
    stage('Test') {
      steps {
        // script
         echo 'Test'
         sh 'mvn test'
         
      }
    }
  }

}
