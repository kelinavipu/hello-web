pipeline {
    agent any

    tools {
        jdk 'jdk 25'
        maven 'Maven 3.9.12'
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}
