pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/Harika444/game-of-life.git', branch: 'master', poll: true, credentialsId: 'Harika444')
      }
    }
  }
}