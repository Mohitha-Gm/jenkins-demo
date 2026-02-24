pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }

        stage('Run Python Script') {
            steps {
                bat '"C:\\Users\\mohit\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" script.py'
            }
        }
    }
}