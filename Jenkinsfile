pipeline {
    agent any
    stages {
        stage('Create directory') {
            steps {
                sh 'bash create-directory.sh'
            }
        }
        stage('Create text file') {
            steps {
                sh 'bash create-file.sh'
            }
        }
        stage('Add information to text file') {
            steps {
                sh 'bash update-file.sh'
            }
        }
        stage('Move text file into prod directory') {
            steps {
                sh 'move-file.sh'
            }
        }
    }
}