pipeline {
  agent any
  stages {
    stage('Build'){
      steps{
        bat 'mvn clean package'
      }      
    }
    stage('Test'){
      steps{
        bat 'mvn test'
      }      
    }
    stage('SonarQube Analysis'){
      steps{
        bat 'mvn sonar:sonar'
      }      
    }
  }
}
