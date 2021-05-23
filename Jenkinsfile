pipeline {
    agent none
    stages {
        stage('build') {
            agent any
            options {
                skipDefaultCheck()
            }
            steps {
                echo "Hello World"
            }
        }
    }
}