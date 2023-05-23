pipeline {
     agent any
     stages {
        stage("Deploy") {
            steps {
                sh "sudo rm -rf /var/www/jenkins-nginx-deploy"
                sh "sudo cp -r ${WORKSPACE}/build/ /var/www/jenkins-nginx-deploy/"
            }
        }
    }
}
