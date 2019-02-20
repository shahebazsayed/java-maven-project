pipeline {
    agent {
        docker {
            image 'maven:3-alpine'
            args '-v /root/.m2:/root/.m2'
        }
    }
    stages {
        stage('step1') {
            steps {
                echo 'hello i am in step 1'
            }
        }
       
           }
}
