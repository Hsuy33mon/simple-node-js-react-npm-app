pipeline {
    agent any

    tools {
        nodejs "Node18"
    }

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}