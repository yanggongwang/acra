pipeline {
  agent any
  stages {
    stage('Example Build') {
      environment {
        agent = 'any'
      }
      steps {
        echo 'Example Build'
      }
    }
  }
  environment {
    agent = 'none'
  }
}