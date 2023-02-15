pipeline {
    agent any
    stages {
        stage("checkout"){
            steps {
                git 'https://github.com/venky9948/Devops.git'
            }
        }
        stage("build"){
            steps {
                sh "mvn clean package"
            }
        }   
    }
}

