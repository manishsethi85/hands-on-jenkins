pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Build'
      }
    }

    stage('Test-Firefox') {
      parallel {
        stage('Test-Firefox') {
          steps {
            echo 'Firefox'
          }
        }

        stage('Test-Edge') {
          steps {
            echo 'Edge'
          }
        }

        stage('Test-Chrome') {
          steps {
            echo 'Chrome1111'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployed'
      }
    }

  }
}