pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'echo "HELLO WORLD"'
        sh '''
          echo "This will list current dir content from latest"
          echo "This is a change"
          echo "This is another change"
          echo "This is the 3rd change"
          echo "This is the 4th change"
          echo "This is the 5th change"
          ls -lh
          '''
      }
    }
    stage ('Test') {
      steps {
        sh 'echo "Hello TEST"'
        sh '''
        echo "This list current dir"
        pwd
        '''
      }
    }
  }
}
