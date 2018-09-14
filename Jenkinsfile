pipeline {
  agent any
  stages {
    stage('BUILD') {
      agent any
      steps {
        echo '"Hello"'
        echo '"end"'
      }
    }
    stage('TEST') {
      steps {
        echo '"Test"'
      }
    }
  }
}