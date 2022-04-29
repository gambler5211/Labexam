pipeline{
  agent any
  stages{
     stage('Testing'){
      steps {
      echo 'running Tests'
      bat 'python exam.py'
      }
     }
      stage('Build'){
       steps{
     echo 'Building jar files...' 
       
     }
   }
 }
}
