pipeline {
    agent any

    stages {
        stage('Help') {
            steps {
                sh './gradlew help '
            }
        }

        stage('Print Env') {
            steps {
                sh 'env'
            }
        }
    }
}
