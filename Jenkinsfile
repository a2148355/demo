node {
    def mvnHome
    stage('????') {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']],
        extensions: [], userRemoteConfigs: [[credentialsId: '11c5120c-2f3c-46c0-9911-bf9d83fb4e64',
        url: 'https://github.com/a2148355/demo.git']]])
    }
    stage('??') {
         sh "mvn -f demo clean package dockerfile:build"
    }
    stage('????') {

    }
}
