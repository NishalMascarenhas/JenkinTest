pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
        mail(subject: 'Testing JTest', body: 'Starting JTest on test server', from: 'nmascarenhas@firstam.com', replyTo: 'nmascarenhas@firstam.com', to: 'nmascarenhas@firstam.com')
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}