pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        timeout(time: 30, unit: 'MINUTES')
        disableConcurrentBuilds()
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
                sh "sleep 10"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo this is Deploy"
            }
        }
    }
}