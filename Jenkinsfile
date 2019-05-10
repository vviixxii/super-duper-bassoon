pipeline {
    agent any
    stages {
        stage('Checkout Git') { 
            steps {
                git poll: true, url: 'https://github.com/vviixxii/super-duper-bassoon.git'
            }
        }
        stage('Clean Stage') {
            steps {
                echo 'Clean Stage'
            }
            //withMaven(maven: 'Maven361') {
            //    sh mvn clean
            //}
        }
        stage('Compile Stage') {
            steps {
                echo 'Compile Stage'
            }
            //withMaven(maven: 'Maven361') {
            //    sh mvn compile
            //}
        }
    }
}
