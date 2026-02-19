pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
		git branch: 'main',
                  url: 'https://github.com/ishagowda/CC_LAB_6.git'
            }
        }

        stage('Build Backend') {
            steps {
                sh 'echo Building backend'
            }
        }

        stage('Build Nginx') {
            steps {
                sh 'echo Building nginx'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deploying containers'
            }
        }
    }
}

