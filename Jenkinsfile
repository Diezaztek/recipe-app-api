pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'docker-compose run --rm test'
            }
        }
    }
}