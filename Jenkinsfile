pipeline {
    agent any

    stages {
        stage('Збірка') {
            steps {
                script {
                    // Виконуємо команду Maven для очищення і збірки проекту в Windows
                    bat 'mvn clean install'
                }
            }
        }
    }
}
