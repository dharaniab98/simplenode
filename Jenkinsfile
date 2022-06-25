pipeline {
    agent : any
    
    stages {
        stage('git check out'){
			steps{
				git credentialsId: 'github', url: 'https://github.com/dharaniab98/simplenode.git'
			}
		}
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}