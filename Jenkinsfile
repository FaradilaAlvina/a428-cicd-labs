node {
    agent{
        docker{
        image 'node:16-buster-slim'
            args '-p 3000:3000'
    }
    }
    checkout scm{
        stage('Build'){
        npm install
    }
    }
}