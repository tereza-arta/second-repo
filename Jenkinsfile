pipeline {
	agent any
	stages {
		stage('Init stage of second repo') {
			steps {
				script {
					def dataFromFirstRepo = env.MY_VARIABLE
					echo "Data from first repo: ${dataFromFirstRepo}"
				}
			}
		}
	}
}
