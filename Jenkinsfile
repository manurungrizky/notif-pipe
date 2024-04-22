pipeline {
    agent any
    
    stages {
        stage('Send Email') {
            steps {
                script {
                    def emailBody = "Hello"
                    emailext(
                        subject: "Hello from Jenkins",
                        body: emailBody,
                        to: "rizkymanurung11@gmail.com"
                    )
                }
            }
        }
    }
}
