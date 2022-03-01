pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'My name is  Taofik'
          }
        }

        stage('Testing') {
          steps {
            echo 'I have 2 boys'
          }
        }

        stage('Test Result') {
          steps {
            echo 'Lola is quite silly'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'SHe just got an SRE job with GCI'
      }
    }

    stage('Production') {
      steps {
        echo 'She starts working tomorrow'
      }
    }

  }
}