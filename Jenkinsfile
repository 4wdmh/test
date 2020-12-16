pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'ls '
                sh 'pwd'
                sh 'ls /var/lib/jenkins/workspace/pipeline_main'
            }
        }
    }
}
