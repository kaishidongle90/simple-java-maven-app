pipeline {
  agent any 
  
  stages {
    stage('Build') {
      environment { 
        liang = 'ming'
    }
      steps {
	echo "Running ${env.BUILD_ID} on ${JENKINS_URL}"
      }
    }
    stage('Test') {
      steps {
	environment { 
       test = 'test123'
    }
        echo 'Testing'
        sh 'printenv'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }
  }
}
