pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'echo "Building ... "'
                sh 'chmod +x linux-build.sh'
                sh 'linux-build.sh'
            }
        }
        stage('Test'){
            steps{
                sh 'echo "Running..."'
                sh 'chmod +x linux-run.sh'
                sh 'linux-run.sh'
            }
        }

    }

}