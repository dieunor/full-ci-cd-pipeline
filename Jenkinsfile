pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        
    }
}
