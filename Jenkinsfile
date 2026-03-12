pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Pulling code from GitHub"
                git 'https://github.com/akshay503yadav-123/again-terraform.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build Stage Running"
            }
        }

        stage('Test') {
            steps {
                echo "Testing Stage Running"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy Stage Running"
            }
        }

    }
}
