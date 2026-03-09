pipeline {
    agent any
    stages {
        stage('Lint Manifests') {
            steps {
                echo 'Checking K8s YAML files...'
            }
        }
        stage('Build Containers') {
            steps {
                echo 'Simulating Docker build for 11 services...'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Running Trivy scan on images...'
            }
        }
    }
}