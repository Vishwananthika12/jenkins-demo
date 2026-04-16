pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Vishwananthika12/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building HTML project..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying project..."
            }
        }
    }
}
