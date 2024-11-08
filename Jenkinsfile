pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Sử dụng checkout scm để clone mã nguồn từ repository đã cấu hình trong phần SCM của job
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

}
}
