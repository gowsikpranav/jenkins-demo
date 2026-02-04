pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code pulled from GitHub repository'
            }
        }

        stage('Build') {
            steps {
                echo 'Building from Jenkinsfile...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing from Jenkinsfile...'
            }
        }
    }

    post {
        success {
            echo 'Build completed SUCCESSFULLY 🎉'
        }
        failure {
            echo 'Build FAILED ❌'
        }
    }
}
