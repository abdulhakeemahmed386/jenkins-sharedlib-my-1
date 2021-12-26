String GHEAccess = 'jenkinsPAT'

library identifier: 'jenkins-sharedlib-my@master', retriever: modernSCM([$class: 'GitSCMSource',
	remote: 'https://github.com/arehmandev/jenkins-sharedlib-my.git',
	credentialsId: GHEAccess])
pipeline {
stages {
 	agent any
        stage("build") {

            steps {
                echo 'building the application...'

            }
        }
        
        stage("test") {

            steps {
                echo 'testing the application'

            }
        }

        stage("deploy") {

            steps {
                echo 'deploying the application...'

            }
        }
    }
}
evenOrOdd(currentBuild.getNumber())

