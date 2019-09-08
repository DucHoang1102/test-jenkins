node ('master'){
    checkout scm

    stage('Build') {
        sh 'echo "Build processing 1"'
        sh 'echo "Build processing 2"'
    }

    stage('Test') {
        sh 'echo "Test processing 1"'
        sh 'echo "Test processing 2"'
    }

    stage('Deploy') {
        sh 'echo "Deploy processing 1"'
        sh 'echo "Deploy processing 2"'
    }
}