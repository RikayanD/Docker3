pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Building...'
                sh "docker build -t rikayand/second_repository:1.0 ."
            }
        }
    }
}
