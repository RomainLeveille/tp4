/*pipeline {
  agent any

  stages {
    stage('Building') {
      steps {
        git url: 'https://github.com/RomainLeveille/tp4.git'
        sh './jenkins/build.sh'
      }
    }

    stage('Testing') {
      steps {
        sh './jenkins/test.sh'
      }
    }

    stage('Deploying') {
      steps {
        sh './jenkins/deploy.sh'
      }
    }
  }
}
*/
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
