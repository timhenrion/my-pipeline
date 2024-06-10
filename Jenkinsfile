pipeline {
    agent { docker.withServer( 'tcp://192.168.1.198:2376' ) { image 'ruby:3.3.2-alpine3.20' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
