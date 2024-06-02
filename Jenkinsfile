pipeline{
    agent any

    stages {
  stage('Build') {
    steps {
      echo 'Build Jenkinsfile'
    }
 }

  stage('Run') {
    steps {
      echo 'waiting 1 minutes for deployment to complete'  
      sleep(60)
    }
  }

  stage('Result') {
    steps {
      echo 'Congratulations'
    }
  }

}
}
