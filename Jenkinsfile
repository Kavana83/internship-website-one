pipeline {
    agent any

    stages {
        stage('Deploy Website One') {
            steps {
                sh '''
                    install -m 664 index.html /var/www/website-one/index.html
                    install -m 664 style.css /var/www/website-one/style.css
                '''
            }
        }
    }
}
