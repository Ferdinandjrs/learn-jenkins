pipeline {
    agent any

    stages {
        stage('1. Tarik Kodingan & Cek Folder') {
            steps {
                echo "Mengintip hasil clone dari GitHub..."
                sh 'ls -la'
            }
        }
        
        stage('2. Simulasi Testing') {
            steps {
                echo "Menjalankan Unit Testing aplikasi..."
                sh 'echo "Running: npm run test... OK!"'
            }
        }

        stage('3. Simulasi Build Image') {
            steps {
                echo "Merakit kodingan jadi Docker Image..."
                sh 'echo "Running: docker build... SUCCESS!"'
            }
        }
    }
}
