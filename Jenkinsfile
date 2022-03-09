pipeline {
    agent any 
    stages {
        stage ("build the application") {
        steps {
            echo 'Build is running'
        }
        }
        stage ("test the application") {
        steps {
            echo 'testing the application'
        }
        }
        stage ("deploy the application") {
        steps {
            echo 'deploying the application'
        }
        }
    }
     post { 
        always { 
            echo 'Running after the stages'
        }
    }
}
