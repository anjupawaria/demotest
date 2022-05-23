node{
    stage('Build') {
        sh '''echo build steps'''
    }
    stage('Test') {
        sh '''echo test steps'''
    }
 stage("Env Variables") {
    
              sh '''printenv'''
}
stage("Env Build Number") {
                echo "The build number is ${env.BUILD_NUMBER}"
                echo "You can also use \${BUILD_NUMBER} -> ${BUILD_NUMBER}" 
}
}
