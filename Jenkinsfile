pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning Repository...'
                git 'https://github.com/Kiran272k/simple-java-devops.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Compiling Java file...'
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running Java program...'
                bat 'java HelloWorld'
            }
        }
    }
}
