pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'npm i'
                sh 'npm test'
            }
        }
    }
}