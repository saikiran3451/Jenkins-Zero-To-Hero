pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                echo 'Cloning from GitHub...'
                // Jenkins already does this automatically if configured in job
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying to production...'
            }
        }
    }
}
