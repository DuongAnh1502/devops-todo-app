pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Clone') {
            steps {
                sh 'https://github.com/DuongAnh1502/devops-todo-app.git'
            }
        }
        stage('Print') {
            steps {
                sh 'ls -la'
            }
        }
        stage('ENd') {
            steps {
                echo 'End World'
            }
        }
    }
}
