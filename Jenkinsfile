pipeline {
    agent any
    stages {
      stage ('Checkout') {
        steps {
          git 'https://github.com/knagu/game-of-life.git'
        }
      }
      stage ('Build') {
        steps {
          sh 'mvn clean package'
        }
      }
    }
}
