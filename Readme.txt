pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Devlop') {
            steps {
                echo 'Deveopling'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
         stage('Releae') {
            steps {
                echo 'rel'
            }
        }
    }
}
