pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Insert actual build command here if needed, e.g., npm install
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Insert your testing command, e.g., npm test
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Add deploy commands, e.g., copy files, restart service
            }
        }
    }
}
