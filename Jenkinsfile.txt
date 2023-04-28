Jenkinsfile
pipeline {
    agent any()
    stages{
        stages 1 ('Environment') {
            steps {
            bat 'env' 
        }

    }
}
}
