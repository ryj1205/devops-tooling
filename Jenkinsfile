pipeline {
    agent any
    stages {
        stage('Create directory') {
            steps {
                sh 'mkdir ~/jenkins-pipelines'
            }
        }
        stage('Create files') {
            steps {
                sh 'touch ~/jenkins-pipelines/file.txt'
            }
        }
    }
}
