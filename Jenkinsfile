pipeline {
    agent any
    import groovy.transform.Field
    stages { 
        stage('checkout SCM') {
            steps {
               checkout scmGit(branches: [[name, '*/test']], UserRemoteConfigs: [[url: 'https://github.com/srinivas-0/sample-pipeline.git']])
            }
        }
    }
}
