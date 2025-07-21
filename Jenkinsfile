pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Sanjuraghava/react-app.git'
            }
        }
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
    }
}
