pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "stage1": {
            echo 'Hi there STage 1'
            
          },
          "stage1B": {
            echo 'stage 1B'
            
          }
        )
      }
    }
    stage('stage2') {
      steps {
        echo 'Hello there too (Stage2)'
      }
    }
  }
  environment {
    NAME = 'WILLIAM'
  }
}