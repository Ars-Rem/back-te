pipeline {
    agent any
    stages {
        stage('back-upload') {
            steps {
                sh "rsync --archive /var/lib/jenkins/workspace/back-te_main test2@192.168.3.233:/var/www/html"
            }
        }
    }
}