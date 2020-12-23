node {
        stage('Create nginx image') {
            sh 'echo "Create nginx image"'
            sh '''
                docker build -t flatigal/web-task .
            '''
        }

        stage('Push image to registry') {
            sh 'echo "Push image to registry"'
            sh '''
                docker push flatigal/web-task
            '''
        }

        stage('Deploy image to web') {
            sh 'echo "Deploy image to web"'
            sh '''
                echo "Deploy image to web"
            '''
        }

}
