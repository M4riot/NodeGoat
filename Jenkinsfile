pipeline{

    agent any

    stages {
        stage('Build TADS') {
            steps {
                sh '''
                    echo "Building TADS"
                    cd tads
                    make
                '''
            }
        }
    }
}