pipeline {
    agent { docker { image 'golang:1.5.0' } }
    stages {
        stage('build') {
            steps {
                sh 'go run sum_test.go'
            }
        }
    }
}

