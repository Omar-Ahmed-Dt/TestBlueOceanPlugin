pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed'
      }
    }

    stage('Test') {
      parallel {
        stage('Test1') {
          steps {
            echo 'First test completed'
          }
        }

        stage('Test2') {
          steps {
            echo 'Second test completed'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Completed'
      }
    }

  }
}