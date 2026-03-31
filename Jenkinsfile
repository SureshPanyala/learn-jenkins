pipeline {
    agent {
        label 'AGENT-1'
    }
    stages {
        stage('Build') {
            steps {
                sh "echo this is BUILD"
                sh "echo this is node version"
            }
        }
        stage('Test') {
            steps {
                sh "echo this is TEST"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo this is Deploy"
            }
        }
    }
}