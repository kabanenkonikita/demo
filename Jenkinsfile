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
        git url: 'https://github.com/kabanenkonikita/demo'
        withMaven {
         cmd "mvn clean verify"
        } // withMaven will discover the generated Maven artifacts, JUnit Surefire & FailSafe reports and FindBugs reports
      }
                }
    }
}