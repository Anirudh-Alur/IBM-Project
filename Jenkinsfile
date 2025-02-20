pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', 
                    credentialsId: 'Anirudh-Alur', 
                    url: 'https://github.com/Anirudh-Alur/Devops-Optimization.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the application..."
                // Add build commands here, e.g., mvn package, npm install, etc.
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                // Add test commands, e.g., pytest, JUnit, Selenium
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the application..."
                // Add deployment steps (Docker, Kubernetes, etc.)
            }
        }
    }
}
