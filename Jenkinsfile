pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3009:3009'
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
