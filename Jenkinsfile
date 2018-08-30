pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Good Morning!'
        sh '''pipeline {
  agent any
  stages {
    stage( \'Good Morning\') {
      steps {
        echo \'Hello World\'
        ah \'java -version\'
       }
      }
    }
}'''
        }
      }
    }
  }