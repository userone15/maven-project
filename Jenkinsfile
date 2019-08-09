pipeline {
  agent any
  stages {
    stage('Build'){
      steps{
        step{
          bat 'mvn clean package'
        }
      }      
    }
  }
}
