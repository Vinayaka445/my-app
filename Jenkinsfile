node{
    stage('SCM Checkout'){
        git 'https://github.com/Vinayaka445/my-app'
    }
    stage('Compile-package'){
        def mvnHome = tool name: 'MAVEN', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
}
