pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
            	git "https://github.com/alhomeronslow02/Jenkins"
            }
        }
        stage('Build') {
            steps {
                sh 'echo "building the app sh command"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests sh command"'
            }
        }
	stage('Deploy') {
            steps {
                sh 'echo "Deploy sh command"'
            }
        }
    }
}
