pipeline {
    agent any

    stages {
        stage('Send Data to Second Repository') {
            steps {
                script {
                    def myData = "Data to be sent from first repository"
                    writeFile file: 'data.txt', text: myData
                    sh 'git config --global user.email "you@example.com"'
                    sh 'git config --global user.name "Your Name"'
                    sh 'git add data.txt'
                    sh 'git commit -m "Adding data file"'
                    sh 'git push origin main'
                }
            }
        }
    }
}
