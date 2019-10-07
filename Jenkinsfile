pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'Init stage'
      }
    }
    stage('Intermediate') {
      steps {
        sh 'echo "Intermediate Stage"'
      }
    }
    stage('Final') {
      steps {
        sh 'echo "ending the pipeline"'
      }
    }
  }
}