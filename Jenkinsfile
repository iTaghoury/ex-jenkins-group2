pipeline {
  agent any
  triggers {
    pollSCM('0 0/2 0 ? * * *')
  }
  
  stages {
    stage('Hello') {
      steps {
        echo 'Hello!'
      }
    }
  }
}
