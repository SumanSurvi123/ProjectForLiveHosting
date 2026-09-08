pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Static HTML project — no build step needed'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployed via GitHub Pages (auto on push to main)'
            }
        }
    }
}
