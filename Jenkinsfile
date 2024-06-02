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
      timeout(time: 60, unit: 'SECONDS') {
}
    }
  }

  stage('Result') {
    steps {
      echo 'Congratulations'
    }
  }

}
}
