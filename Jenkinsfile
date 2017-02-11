pipeline {
    agent any

    stages {

        stage('build') {
            echo 'building'
            sh 'make'
        }

        stage('test') {
            echo 'testing'
            sh 'make test'
        }

        stage('deploy') {
            echo 'deploying'
        }
    }
}