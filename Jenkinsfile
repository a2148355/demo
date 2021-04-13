node {
    def mvnHome
    stage('goujian') {
       sh "mvn -v"
    }
    stage('dabao') {
         sh "mvn -f demo clean package dockerfile:build"
    }
    stage('dengdeng') {

    }
}
