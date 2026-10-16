pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Downloading Website One from GitHub'
            }
        }

        stage('Deploy Website One') {
            steps {
                sh '''
                    sudo cp index.html /var/www/website-one/index.html
                    sudo cp style.css /var/www/website-one/style.css
                '''
            }
        }
    }
}
