pipeline {
  agent {
    label 'jdks'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Good Morning!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Aruna'
  }
}