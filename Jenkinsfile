pipeline{
    agent any
    stages{
        stage('checkout')
        {
          steps{
             git branch: 'main', url: 'https://github.com/zaid-coder-01/zaid-coder-01.git'
          }
        }
         stage('build')
        {
            steps{
              sh 'docker-compose up --build'
            }
        }
    }
}
