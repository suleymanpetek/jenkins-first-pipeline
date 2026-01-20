pipeline {
    agent any
    stages {
        stage('Environment Check') {
            steps {
                echo 'Python versiyonu kontrol ediliyor...'
                sh 'python3 --version'
            }
        }
        stage('Run Python Script') {
            steps {
                echo 'Python uygulamasi calistiriliyor...'
                sh 'python3 hello.py'
            }
        }
    }
}
