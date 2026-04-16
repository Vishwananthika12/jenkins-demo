pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building project..."
            }
        }

        stage('Deploy') {
            steps {
                sh 'cp index.html /var/www/html/index.html'
            }
        }
    }
}
}
