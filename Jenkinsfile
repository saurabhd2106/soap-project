pipeline {
    agent any

    stages {
        
        stage('Execute tests') {
            steps {
               sh '/home/ubuntu/SmartBear/SoapUI-5.7.0/bin/testrunner.sh conduitApplicationTests.xml'
            }
        }
    }
}
