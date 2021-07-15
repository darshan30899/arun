pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'this is a buid stage'
            }
        }
        stage('test') {
            steps {
                echo 'this is a test stage'
            }
        }
        stage('deploy') {
            steps {
                echo 'this is deploy stage'
            }
        }
        stage('staging') {
            steps {
                echo 'this is deploy on staging server'
            }
        }
        stage('production') {
            steps {
                echo 'this is deploy on production server'
            }
        }
    }
}
