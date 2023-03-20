pipeline {
  agent any 
  tools {
    maven 'Maven'
stages{
  satge('Intialization'){
    steps {
      ''' 
        echo "PATH = ${PATH}"
        echo "M2_HOME"= $ {M2_HOME}"
    }
   stage('Build'){
     sh 'mvn clean package'
   }
}
}



