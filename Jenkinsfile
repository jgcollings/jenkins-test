pipeline {
    agent any

    stages {
        checkout scm
        
        stage('build') {
            steps {
                echo 'building'
                sh 'make'
            }
        }

        stage('test') {
            steps {
                echo 'testing'
                sh 'make test'
            }
        }

        stage('deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
}