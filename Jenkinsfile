node {
        stage('Create/Push nginx image') {
            sh 'echo "Create/Push nginx image"'
            build job: 'create-nginx-image'
        }

        stage('Deploy image to web') {
            sh 'echo "Deploy image to web"'
            build job: 'deploy-web'
        }
}
