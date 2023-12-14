pipeline {
  agent any
  stages {
    stage('Test stage') {
      parallel {
        stage('Test ') {
          steps {
            echo 'testing stage'
          }
        }

        stage('Dev ') {
          steps {
            echo 'dev stage'
          }
        }

        stage('Plugin ') {
          steps {
            echo 'plugin stage'
          }
        }

      }
    }

    stage('QA ') {
      steps {
        echo 'qa stage'
      }
    }

    stage('UAT ') {
      steps {
        echo 'uat stage'
      }
    }

    stage('Deploy ') {
      steps {
        echo 'deployment stage'
      }
    }

    stage('Operator') {
      steps {
        echo 'operating stage'
      }
    }

  }
}