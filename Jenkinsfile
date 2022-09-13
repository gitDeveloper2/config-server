pipeline {
    agent any

    stages {
        stage('git Build') {
            steps {
                echo 'git Building'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        post{
            success{
            echo 'success
            }
        }
        
    }
}
