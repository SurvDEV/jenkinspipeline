pipeline {
  agent any
  stages {
    stage('Fetch sources') {
      steps {
        git(url: 'https://github.com/SurvDEV/simple-java-maven-app.git', branch: 'master', credentialsId: 'lol1337')
      }
    }
  }
}