pipeline {
    agent { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world2!'
            }
        }
                stage('build') {
                    steps {
                        sh 'mvn --version'
                    }
                }
    }
}