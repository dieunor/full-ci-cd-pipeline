pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Code Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
