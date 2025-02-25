pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/KhanhNb2k/khanhnb13.git'
            }
        }
        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the project..."
            }
        }
    }
}
