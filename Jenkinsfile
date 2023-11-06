properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
              bat 'echo %TIME%'
              bat 'echo %TIME%'
            }
        }
    }
}

