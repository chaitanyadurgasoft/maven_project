pipeline{
agent {
        label 'Dev'
        
    }
    stages{
        stage('build'){
            steps{
               sh(script: "mvn clean install")
            }
        }
    }
}