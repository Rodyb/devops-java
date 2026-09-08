#!/usr/bin.env groovy

pipeline {   
    agent any
    stages {
        stage("test1") {
            steps {
                script {
                    echo "Testing the application..."

                }
            }
        }
        stage("build") {
            steps {
                script {
                    echo "Building the application..."
                }
            }
        }

        stage("deploy") {
            steps {
                script {
                    echo "Deploying the application..."
                }
            }
        }               
    }
} 
