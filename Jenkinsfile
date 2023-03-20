pipeline {
  agent any 
  tools {
    maven 'Maven'
  }
stages{
  stage('Intialized'){
    step {
      ''' 
        echo "PATH = ${PATH}"
        echo "M2_HOME"= $ {M2_HOME}"
      '''
    }
  }
   stage('Build'){
     step{
      sh 'mvn clean package'
    }
   }  
  }
}
