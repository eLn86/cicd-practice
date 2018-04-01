pipeline {
agent {label 'AWS'}

  stages {
    stage('Build'){
      steps {
      checkout scm
      sh 'mvn package'
      }
    }
    stage('Deploy'){
      steps {
        echo "Deploy is successfull"
      }
    }
  }
}
