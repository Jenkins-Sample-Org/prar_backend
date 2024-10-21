pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Doctor') {
            steps {
                echo 'Welcome Doctor'
            }
        }
        stage('Backend') {
              steps {
                  echo 'Welcome to Backend'
              }
          }
    }
}
