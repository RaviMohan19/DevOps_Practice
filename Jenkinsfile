pipeline{
    agent {
        node {
            label 'master'
        }
    }
    

    stages {
        stage('Build') {
            steps {
                echo "This is Build Stage"
            }
        }
        
        stage('Test') {
            steps {
                echo "This is Testing Stage"
            }
        }
        
        stage('DeployStaging') {
            steps {
                echo "This is Deploy stage"
            }
        }
    }
}
