pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world2!'
            }
        }
                stage('Build') {
                    steps {
                        sh 'mvn -B -DskipTests clean package'
                    }
                }
    }
}