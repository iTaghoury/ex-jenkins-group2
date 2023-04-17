pipeline {
  agent any
  triggers {
    pollSCM('H/2 * * * *')
  }
  
  stages {
    stage('Hello') {
      steps {
        echo 'Hello!'
      }
    }
  }
}
