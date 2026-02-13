pipeline {
    agent any

    tools {
        jdk 'jdk 25'
        maven 'Maven3'
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}
