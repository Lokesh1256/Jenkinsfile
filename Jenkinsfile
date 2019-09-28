pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build job: 'DemoWhenDeveloperCommitsCodeAutoRunJenkinsfile', quietPeriod: 0
                echo 'builded'
                echo 'Building..'
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
