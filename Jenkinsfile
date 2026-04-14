pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/shreyas-babar/addition.git'
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python add.py'
            }
        }
    }
}
