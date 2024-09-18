pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Input Choice') {
            steps {
                script {
                    // def update_deployment_render = input message: 'Please select a deployment manifest',
                    //     parameters: [
                    //         choice(choices: ['manifest1', 'manifest2', 'manifest3'], name: 'manifest', description: 'Choose your deployment manifest'),
                    //         booleanParam(name: "sonar", defaultValue: false, description: "отчет в sonar"),
                    //         booleanParam(name: "test", defaultValue: true, description: "запуск gradle тестов")
                    //     ]
                    // echo "Selected manifest: ${update_deployment_render}"
                    sh 'pwd'
                    sh 'ls -la'
                }
            }
        }
    }
}
