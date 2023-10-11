pipeline{
  agent any 
  stages{
    stage('Deploy'){
      steps{
        echo "Test Successful"
      bat"mvn compile"
      }
    }
    stage('Build'){
      steps{
        echo "build succesful"
      bat "mvn clean"
      }
    }
    stage('Test'){
      steps{
        echo "test succesful"
      bat "mvn test"
      }
    }
  }
}

  
    
