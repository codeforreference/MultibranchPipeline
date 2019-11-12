pipeline {
    stages {
        stage('Master') {

            steps {
                when {
                branch 'Master'
            }
                git 'https://github.com/codeforreference/MultibranchPipeline.git'
            }
        }
    }
}