pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/jenkinsci/jenkins', branch: 'master', changelog: true, poll: true, credentialsId: 'd3228b63b1b588d27003747f6ec61b71e802fe38')
      }
    }
  }
}