pipeline{
 agent any

 stages{

  stage('Docker'){
   steps{
    bat 'docker build -t web .'
    bat 'docker run -d -p 9090:80 web'
   }
  }

 }

}