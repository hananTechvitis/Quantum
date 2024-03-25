pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'mvn -B clean install' // Runs Maven build
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'mvn test' // Runs Maven tests
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
