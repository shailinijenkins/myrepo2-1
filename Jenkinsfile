pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          agent any
          steps {
            sh 'echo "stage1"'
          }
        }

        stage('stage2') {
          agent any
          steps {
            echo 'stage2'
          }
        }

      }
    }

  }
}