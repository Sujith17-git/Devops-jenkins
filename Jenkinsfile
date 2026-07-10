pipeline {

    agent any

    stages {

        stage('Compile') {
            steps {
                bat 'javac Spidey.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Spidey'
            }
        }

    }
}
