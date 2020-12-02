pipeline {
  agent any
  stages {
    stage('Build stage') {
      steps {
        sh ' mvn -B -DskipTests clean package '
      }
    }

    stage('Test stage') {
      steps {
        sh 'mvn test'
        echo 'First Test case -ozj___'
        echo 'Second Test Case - ozj___'
      }
    }

    stage('Deliver Stage') {
      steps {
        echo 'Reached Delivery - ozj___'
      }
    }

  }
}