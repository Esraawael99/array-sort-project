pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
                git 'https://github.com/Esraawael99/array-sort-project.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add your build steps here (e.g., compile, test)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add your deployment steps here (e.g., Docker push)
            }
        }
    }
}
