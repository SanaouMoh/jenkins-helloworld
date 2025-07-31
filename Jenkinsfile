node {
    stage('clone') {
        chechout scm
     }
    stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'
     }
}
