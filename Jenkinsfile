pipeline {
  agent any 
  stage {
    stage('Build'){
      steps{
        // Assuming java is in the system path
        bat 'java Money.java'
      }
    }
    stage('Test'){
      steps{
        bat 'java MoneyTest.java'
      }
    }
  }
}
