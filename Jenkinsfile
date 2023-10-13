pipeline {
    agent {
        docker {
            image 'node:16' // Use Node.js 16 Docker image
            args '-u 1000:1000' // Optional: Set the user to avoid permission issues
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install --save'
            }
        }
    }
}

