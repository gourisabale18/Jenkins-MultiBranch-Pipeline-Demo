pipeline {
  agent any

  stages {
    stage("build") {
      steps {
        container ('maven'){
          sh 'mvn clean package'
        }
      }
    }
    stage("test") {
      steps {
        echo 'Testing the application...'
      }
    }
    stage("deploy") {
      steps {
        echo 'Deploying the application...'
        
      }
    }
  }
}
