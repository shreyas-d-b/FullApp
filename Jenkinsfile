pipeline {
    agent any

    stages{
        stage('Run') {
            steps {
                  bat 'docker build -t web .'
                  bat 'docker run -d -p 8080:80 web'
            }

        }
    }
}