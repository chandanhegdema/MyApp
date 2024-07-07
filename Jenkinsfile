pipeline {
    agent any
triggers{
    pollSCM '*/1/****'
}
    stages {
        stage('ch perm') {
            steps {
                sh('chmod 777 hello.sh')
            }
        }
      stage('run') {
            steps {
                sh('./hello.sh')
            }
        }
    }
}
