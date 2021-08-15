pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'in Build'
        sh 'mvn -B -DskipTests clean package'
      }
    }

    stage('Test') {
      steps {
        echo 'Test'
        sh 'mvn test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}