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
pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO WORLD"'
      sh '''
        echo "This will list current dir content"
        ls -lh
        '''
      }
    }
  }
} 
