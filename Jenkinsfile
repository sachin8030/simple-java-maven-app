pipeline {
    agent any
    stages {
        stage("Checkout scm") {
            steps {
                script {
                    echo 'checkout scm....'
                }
            }
        }
        stage("Build") {
            steps {
                script {
                    echo 'Build....'
                }
            }
        }
        stage("Sonar Build") {
            steps {
                script {
                    echo 'Running Sonar scanning....'
                }
            }
        }
        stage("Testing") {
            steps {
                script {
                    echo 'Running Tests....'
                }
            }
        }
        stage("Upload Artifact") {
            steps {
                script {
                    echo 'Upload Artifact....'
                }
            }
        }
    }
}
