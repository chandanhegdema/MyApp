pipeline {
    agent any

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
