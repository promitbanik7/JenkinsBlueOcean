pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building'
          }
        }

        stage('Parallel Build') {
          steps {
            echo 'Parallel Building'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test Sucessful'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment Completed'
      }
    }

  }
}