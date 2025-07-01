pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Git stage'
		git "https://github.com/alhomeronslow02/Jenkins"
            }
        }
        stage('Build') {
            steps {
                echo 'Build image'
		sh 'echo "building the app sh command"'
            }
        }
        stage('Test') {
            steps {
                echo 'Test the app'
		sh 'echo "Running tests sh command"'
            }
        }
	stage('Deploy') {
            steps {
                echo 'Deploy the app'
		sh 'echo "Deploy sh command"'
            }
        }
    }
}
