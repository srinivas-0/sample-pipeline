pipeline {
    agent any
    stages { 
        stage('checkout SCM') {
            steps {
                git (
                    url: https://github.com/srinivas-0/sample-pipeline.git
                    branch: "${branch}"
                )
            }
        }
    }
}
