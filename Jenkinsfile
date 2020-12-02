pipeline {
  agent any
  stages {
    stage('Build stage') {
      steps {
        bat(script: ' mvn -B -DskipTests clean package ', encoding: 'UTF-8')
      }
    }

    stage('Test stage') {
      steps {
        bat(script: 'mvn test', encoding: 'UTF-8')
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