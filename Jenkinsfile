pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "echo this is BUILD"
                sh "echo this is updated version"
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