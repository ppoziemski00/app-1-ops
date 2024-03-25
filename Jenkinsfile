pipeline {
    agent any // Określa, że pipeline może być wykonany na dowolnym agencie
    parameters {
        string(name: 'GREETING', defaultValue: 'Hello', description: 'The greeting message')
        choice(name: 'BRANCH', choices: ['master', 'dev'], description: 'Branch to build')
    stages {
        stage('Build') { // Etap budowania
            steps {
                echo 'Building...'
            }
        }
        stage('Test') { // Etap testowania
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') { // Etap wdrażania
            steps {
                echo 'Deploying...'
            }
        }
    }
}
