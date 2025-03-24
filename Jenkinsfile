pipeline {
    agent any

    stages {
        stage('Git Clone') {
            steps {
                git 'https://github.com/yogeshcoded/gradle-demo.git'
            }
        }
        stage('build') {
            steps {
                bat 'gradle clean build'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
