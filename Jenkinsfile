pipeline {
    agent any

    stages {
        stage('First') {
            steps {
                sh 'echo $PATH'
            }
        }
        stage('Second') {
            steps {
                sh 'echo HELLO'
                sh 'echo "this is second step"'
            }
        }
    }
}
