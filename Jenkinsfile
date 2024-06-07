pipeline {
  agent any

  stages {
    stage('build') {
      steps {
        echo 'Building the application...'
        sh 'mvn clean package -DskipTests'
      }
    }
    stage('test') {
      steps {
        echo 'Testing the application...'
      }
    }
    stage('deploy') {
      steps {
        echo 'Deploying the application...'
        
      }
    }
  }
}
