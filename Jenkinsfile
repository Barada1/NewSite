pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'fix', url: 'https://github.com/Barada1/NewSite.git'
            }
        }

        stage('Run Script') {
            steps {
                sh '''
                    ls -l
                    chmod +x script3.sh
                    ./script3.sh
                '''
            }
        }
    }
}
