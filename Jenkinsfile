node {
    stage('Clone Repository') {
        git branch: 'main',
            url: 'https://github.com/Aryan-Jagtap/Hello-World.git'
    }

    stage('Build') {
        echo 'Building the application...'
        sh 'echo Build Complete'
    }

    stage('Deploy') {
        echo 'Deploying the application...'
        sh 'bash hello.sh'
    }
}
