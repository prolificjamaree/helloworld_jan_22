pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
                slows 5
            }
        }
                stage('build') {
            steps {
                echo 'build'
                slows 5
            }
        }
                stage('test') {
            steps {
                echo 'test'
                slows 5
            }
        }
                stage('deploy') {
            steps {
                echo 'deploy'
                slows 5
            }
        }
    }
}
