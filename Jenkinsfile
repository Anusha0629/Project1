node {
    stage('SCM-checkout') {
        git 'https://github.com/Anusha0629/Project1.git'
}
    stage('compile-package'){
        def mvnhome= tool name: 'maven_home', type: 'maven'
        sh "${mvnhome}/bin/mvn package"
    }
}
