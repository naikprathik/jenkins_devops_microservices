pipelines{
agent {docker{images'Java:3.6.3'}}
stages{
       stage('Build') {
       steps{
             sh 'Java --version'
             echo "Build"
	     
	       }
	  }
	  
	  
       stage('Test') {
       steps{
             echo "Test"
            }
	  
       stage('Integration Test') {
       steps{
             echo "Integration Test"
	       }
	  }
	  
     }
}
}
