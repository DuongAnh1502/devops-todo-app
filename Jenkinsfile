pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('View') {
            steps {
                dir('views') {
                    sh 'ls -la'
                }
            }
        }
        stage('ENd') {
            steps {
                echo 'End World'
            }
        }
    }
}
