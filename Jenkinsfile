pipeline {
    agent any

    tools {
        maven 'maven399'   // 这里的名字，必须和全局工具配置里的名字一致
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
