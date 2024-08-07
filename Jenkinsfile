pipeline {
    agent any
    triggers {
        pollSCM('* * * * *')
    }
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'develop', url: 'https://github.com/Ratnesh10101/pipeline-demo.git'
            }
        }
    }
}
