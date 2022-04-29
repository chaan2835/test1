
pipeline {
    agent none
    stages {
        stage('Example Build') {
            steps {
                sh 'echo Hello World'
            }
        }
        stage('Ready to Deploy') {
            steps {
                input(message: "Deploy to production?")
            }
        }
        stage('Example Deploy') 
            steps {
                sh 'echo Deploying'
            }
        }
    }
}
