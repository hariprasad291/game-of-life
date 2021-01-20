node('CENTOS'){
    stage('scm'){
        git 'https://github.com/hariprasad291/game-of-life.git'
    }
    
    stage('build'){
        sh 'mvn package'
    }
    
    
}
