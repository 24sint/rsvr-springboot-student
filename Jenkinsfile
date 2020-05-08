  
pipeline {
  agent any
  tools{
        maven 'Default'
      }
  stages {
    stage('Jenkinffile Test') {
      steps {
        sh "mvn -v"
      }
    }
  }
}
