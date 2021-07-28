pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO WORLD"'
      sh '''
        echo "This is a change"
        ls -lh
        '''
      }
    }
  }
} 
