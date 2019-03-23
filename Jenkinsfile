pipeline {
    agent any
    stages {
        stage('git_clone') {
            steps {
                echo 'Hello world!' 
                sh '''
                git clone https://github.com/madhukumarsurya/madhu.git
                '''
            }
        }
    stage('Build') {
        steps {
            echo 'helloword'
            sh '''
            mvn clean
            mvn compile
            mvn test
            mvn package
            '''
        }
    }
    stage('Unittests') {
        steps {
            echo 'helloword'
        }
    }
    stage('sonar') {
        steps {
            echo 'helloword'
        }
    }
    stage('artifactory') {
        steps {
            echo 'helloword'
        }
    }
    stage('deploy') {
        steps {
            echo 'helloword'
        }
    }
    }
}
