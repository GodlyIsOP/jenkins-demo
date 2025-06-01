pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/your-username/jenkins-demo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying..."'
                sh 'cp index.html /var/www/html/'
            }
        }
    }
}
