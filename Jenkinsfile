pipeline{
    agent any
    stages{
    
      stage('Test'){
          steps{
          bat 'mvn test'
          }
      }
      stage('Build'){
          steps{
          bat 'mvn install'
          }
      }
      stage('Deploy'){
          steps{
          bat 'mvn deploy'
          }
      }
      
    }
}
