pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build job: 'DemoWhenDeveloperCommitsCodeAutoRunJenkinsfile', quietPeriod: 0
                echo 'Building..'
                sh 'ls -la'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'ls -la'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
