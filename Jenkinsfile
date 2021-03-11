pipeline {
    agent { label 'main' }
    stages {
        stage('build') {
            steps {
                echo 'Hello World!'
            }
        }
    }
    post {
    failure {
      mail to: iskidet@gmail.com, subject: ‘The Pipeline failed :(‘
    }
  }
}
