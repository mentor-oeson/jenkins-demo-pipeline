pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running build script...'
                sh './build.sh'
            }
        }
        stage('Test') {
            steps {
                echo 'Running test script...'
                sh './test.sh'
            }
        }
    }
}
