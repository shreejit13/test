pipeline {
    agent any
    stages {
        stage('checkout git') {
            steps {
                echo 'checkout git'
            }
        }

        stage('build') {
            steps {
                echo 'build'
            }
        }

        stage ('test') {
            steps {
                echo 'test'
            }
        }

        stage('deploy development'){
            steps {
                echo 'dev'
            }
        }

        stage('deploy staging'){
            steps {
                echo 'stage'
            }
        }

        stage('deploy production'){
            steps {
                echo 'prod'
            }
        }
    }
}
