pipeline{
    agent any
    stages {
        stage('Initialize'){
            steps{
                sh '''
                echo "1PATH = ${PATH}"
                echo "M2_HOME  = ${M2_HOME}"
                   '''
            }
        }
        stage('Build'){
            steps {
                echo "Hello World!"
            }
        }
    }
}
