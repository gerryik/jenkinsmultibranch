pipeline {
    agent any
    stages {
        stage('Main Branch Deploy Code') {
            when {
                branch 'main'
            }
            steps {
                sh 'echo "Building Artifact from Main branch"'
 
                sh 'echo "Deploying Code from Main branch"'
            }
        }
        stage('Develop Branch Deploy Code') {
            when {
                branch 'develop'
            }
            steps {
                sh 'echo "Building Artifact from Develop branch"'
                sh 'echo "Deploying Code from Develop branch"'
           }
        }
                stage('Develop Branch Deploy Code') {
            when {
                branch 'feature'
            }
            steps {
                sh 'echo "Building Artifact from feature branch"'
                sh 'echo "Deploying Code from feature branch"'
           }
        }
            stage('Develop Branch Deploy Code') {
            when {
                branch '112b'
            }
            steps {
                sh 'echo "Building Artifact from 112b branch"'
                sh 'echo "Deploying Code from De112bvelop branch"'
           }
        }
        stage('Develop Branch Development of Code') {
            when {
                branch '112a'
            }
            steps {
                sh 'echo "Building Artifact from 112b branch"'
                sh 'echo "Deploying Code from De112bvelop branch"'
           }
        }
    }
}
