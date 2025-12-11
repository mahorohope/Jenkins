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
                echo 'No build needed for this repository.'
                // If a Node project exists later, you can uncomment:
                // script {
                //     if (fileExists('package.json')) {
                //         bat 'npm install'
                //     } else {
                //         echo 'No package.json found, skipping npm install.'
                //     }
                // }
            }
        }
        stage('Test') {
            steps {
                echo 'No tests to run for this repository.'
                // If Node project tests exist:
                // script {
                //     if (fileExists('package.json')) {
                //         bat 'npm test'
                //     } else {
                //         echo 'No package.json found, skipping tests.'
                //     }
                // }
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
