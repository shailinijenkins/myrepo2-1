pipeline {
  agent none
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "stage1"'
          }
        }

        stage('stage2') {
          steps {
            echo 'stage2'
          }
        }

      }
    }

    stage('stage3') {
      steps {
        sleep 5
      }
    }

  }
}