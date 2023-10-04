/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'docker/welcome-to-docker:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                echo 'Prueba 1'
            }
        }
    }
}