//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'node:latest' }  }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
