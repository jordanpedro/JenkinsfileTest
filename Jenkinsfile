pipeline{
    agent any
    stages {
        stage('Initialize'){
            steps{
                cmd '''
                echo "2PATH = ${PATH}"
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
