pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        parallel(
          "Build": {
            echo 'hello'
            
          },
          "stuff": {
            echo 'sdf'
            
          }
        )
      }
    }
    stage('Test') {
      steps {
        parallel(
          "Chrome": {
            echo 'testing in chrome'
            
          },
          "Firefox": {
            echo 'testing in firefox'
            
          },
          "Yotam1": {
            sh 'echo 1'
            
          }
        )
      }
    }
    stage('Deploy') {
      steps {
        echo 'deploying'
      }
    }
    stage('asdasd') {
      steps {
        echo 'asd'
      }
    }
  }
}
