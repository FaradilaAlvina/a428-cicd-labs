node {
    checkout scm
    docker.image('node:16-buster-slim').withRun('-p 3000:3000')
    stage('Build') {
        sh "npm install"
    }
}

// node {
//     agent{
//         docker{
//         image 'node:16-buster-slim'
//             args '-p 3000:3000'
//     }
//     }
//     checkout scm{
//         stage('Build'){
//         sh "npm install"
//     }
//     }
// }