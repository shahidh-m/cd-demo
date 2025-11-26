pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/shahidh-m/cd-demo'
            }
        }

        stage('Build') {
            steps {
                echo "Build step completed successfully"
            }
        }

        stage('Deploy') {
            steps {
                echo "Application deployed successfully!"
            }
        }
    }
}
