pipeline{
  agent any
  stages{
    stage('checkout'){
      steps{
          git branch: 'main', url: 'https://github.com/iqbal19900820/new.git'
      }
    }
    stage('run'){
      steps{
        sh 'docker-compose up --build -d'
             
      }
    }
  }
}
