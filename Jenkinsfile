pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/NAGAGIT1/php-deploy.git'
            }
        }

        stage('Deploy') {
            steps {
                sh 'sudo cp -r * /var/www/html/'
            }
        }
    }
}

