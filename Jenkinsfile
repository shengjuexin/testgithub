pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building...'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
	  echo "--------------------------------------"
        }
   }
   stage('Test') {
     steps {
        echo 'Testing...'
	  echo "--------------------------------------"
     }
   }
   stage('Deploy') {
     steps {
       echo 'Deploying...'
	  echo "--------------------------------------"
     }
   }
  }
}
