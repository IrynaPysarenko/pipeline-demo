pipeline {
    agent any
    libraries {
        lib('library-demo@master')
    }
    stages {
        stage('Demo') {
            steps {
                hello 'sometext'
            }
        }
    }
}