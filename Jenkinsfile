pipeline {
    agent ('any')
    stages {
        stage('git_clone_demo') {
            steps {
                sh'''
                pwd
                ls -ll
                rm -rf *
                git clone 'https://github.com/redprasa/Pipeline_All_Tools.git'
                '''
            }
        }
    stage('Build') {
        steps {
            echo 'Maven_Test'
            sh '''
           echo 'install maven'
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
