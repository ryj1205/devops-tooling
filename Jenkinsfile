pipeline {
    agent any
    stages {
        stage('Create directory') {
            steps {
                sh 'mkdir ~/jenkins-pipelines || true'
            }
        }
        stage('Create files') {
            steps {
                sh 'touch ~/jenkins-pipelines/file.txt'
                sh 'ls -al'
            }
        }
    }
}
