pipeline {
    agent any
    stages { 
        stage('checkout SCM') {
            steps {
               checkout([$class: 'GitSCM', branches: [[name, '*/test']], UserRemoteConfigs: [[url: 'https://github.com/srinivas-0/sample-pipeline.git']]])
            }
        }
    }
}
