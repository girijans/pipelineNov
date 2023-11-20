
pipeline {
    agent any
    stages {
       stage ('checkout'){
          steps {
	      sh 'ls'
	      sh 'cat Jenkinsfile'
             }
	  }
       stage ('build'){
         steps {
	      echo " I am Build stage "
	     }
      }
      stage('test'){
          steps {
	      echo " I am Test stage"
              }
        }
     stage('deploy'){
           steps{
	        echo " I am deploy stage"
	      }
    }
    stage('Unit test'){
           steps{
	      echo " I am Unit test stage"
	     }
     }
     stage('delivery stage'){
          steps{
	      echo" I am delivery stage"
	      }
       }
  }
}
       
