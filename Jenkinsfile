#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building....'
				sh "ls -ltra"
				#sh "cmake ./CMakeLists.txt"
				#sh "make -f Makefile"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}