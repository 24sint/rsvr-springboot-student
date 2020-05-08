  
pipeline {
  agent any
  tools{
        maven 'maven:3-alpine'
      }
  stages {
    stage('Jenkinffile Test') {
      steps {
        sh "mvn -v"
      }
    }
  }
}
