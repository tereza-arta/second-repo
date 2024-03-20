pipeline {
    agent any
    
    parameters {
        string(name: 'DATA_TO_RECEIVE', description: 'Data received from Repository 1')
    }
    
    stages {
        stage('Receive Data') {
            steps {
                script {
                    // Access the received data
                    def receivedData = params.DATA_TO_RECEIVE
                    echo "Received Data: ${receivedData}"
                    
                    // Now you can proceed with further processing using the received data
                }
            }
        }
    }
}
