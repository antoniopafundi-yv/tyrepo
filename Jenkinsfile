pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        echo 'building the applicaiton...'
      }
    }
    
    stage("test"){
      steps{
        echo 'testing the applicaiton...'
      }
    }
    
    stage("deploy"){
      steps{
        echo 'deploy the applicaiton...'
      }
    }
  }
  
  post {
    always {
        junit '**/target/*.xml'
    }
  }
  
}
