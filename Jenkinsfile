pipeline {
  agent any
  stages {
    stage('Plan') {
      steps {
        echo 'i have a plan to work on ci/cd pipeline'
      }
    }

    stage('Code') {
      steps {
        echo ' i have code  to work on ci/cd pipeline'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'i have a build to work on ci/cd pipeline'
          }
        }

        stage('Test') {
          steps {
            echo ' i have test to work on ci/cd pipeline'
          }
        }

        stage('Release') {
          steps {
            echo ' i have release to work on ci/cd pipeline'
          }
        }

        stage('Deploy') {
          steps {
            echo ' i have deploy to work on ci/cd pipeline'
          }
        }

        stage('Operate') {
          steps {
            echo 'i have a operate to work on ci/cd pipeline'
          }
        }

      }
    }

  }
}