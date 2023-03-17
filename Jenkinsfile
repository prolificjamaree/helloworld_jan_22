pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
                slow 5
            }
        }
                stage('build') {
            steps {
                echo 'build'
                slow 5
            }
        }
                stage('test') {
            steps {
                echo 'test'
                slow 5
            }
        }
                stage('deploy') {
            steps {
                echo 'deploy'
                slow 5
            }
        }
    }
}
