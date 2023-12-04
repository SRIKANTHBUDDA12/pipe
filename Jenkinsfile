pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'building '
          }
        }

        stage('impliment') {
          steps {
            echo 'implement the code'
          }
        }

      }
    }

    stage('develop') {
      parallel {
        stage('develop') {
          steps {
            echo 'develop the code'
          }
        }

        stage('test') {
          steps {
            echo 'testing'
          }
        }

      }
    }

    stage('environment') {
      parallel {
        stage('environment') {
          steps {
            echo 'to environment'
          }
        }

        stage('adding') {
          steps {
            echo 'adding'
          }
        }

      }
    }

    stage('end') {
      steps {
        echo 'ending'
      }
    }

  }
}