pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3003:3003' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}