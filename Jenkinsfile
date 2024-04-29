pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Obs3rve/thesis.git'
            }
        }
        stage('Build') {
            steps {
                sh 'python hello_world.py'
            }
        }
    }
}
