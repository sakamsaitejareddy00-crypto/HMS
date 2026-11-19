pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
                bat "mvn clean"
            }
        }
        stage('Install and package') {
            steps {
                bat "mvn install package"
            }
        }
        stage("Test"){
            steps{
                bat "mvn test"
            }
        }
    }
}
