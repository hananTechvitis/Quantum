pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'docker run -p 80:80 -d --name hanan httpd' // Runs Maven build
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment commands here. This will depend on your application and infrastructure.
            }
        }
    }
}
