peline{
    agent any
    stages{
        stage('Code') {
            steps{
            git credentialsId: '28439e79-0b84-4e66-ae8c-b03f67a83d70', url: 'https://github.com/snehabadam/example.git'
        }
        }
    
      stage('Build'){
          steps{
       sh 'mvn package'
        }
        
      }
    }
    
}
