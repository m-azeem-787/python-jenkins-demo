pipeline {
    agent {
        docker { 
            image 'python:3.11'
        }
    }
    stages {
        stage('Run Calculator') {
            steps {
                sh 'python3 calculator.py'
            }
        }
    }
}
