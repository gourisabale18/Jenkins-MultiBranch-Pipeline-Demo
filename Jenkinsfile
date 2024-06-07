pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo "Building the application..."
        sh 'mvn clean package -DskipTests'
      }
    }
    stage('Test') {
      steps {
        echo "Testing the application..."
        // Add your testing steps here
      }
    }
    stage('Deploy') {
      steps {
        echo "Deploying the application..."
        // Add your deployment steps here
      }
    }
  }
}
