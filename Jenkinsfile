pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                  echo 'Building..'
                  bat 'mvn clean package' 
            }
        }
        stage('Deploy') { 
            steps {
                  echo 'Deploying....'
            }
        }
    }
}
