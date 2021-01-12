node {
    stage ('scm checkout '){
        git credentialsId: 'Github', url: 'https://github.com/bvsdeepika/maven.git'
    }
    stage ('build'){
        sh 'mvn -f web/pom.xml clean package '
    }
    stage ('test'){
        echo 'test'
    }
    stage ('security scanner'){
        echo 'scanning'
    }
    stage ('approval'){
    echo 'approval'
}
stage ('Deploy'){
    echo 'Deploy'
}
}
