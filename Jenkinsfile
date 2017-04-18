pipeline {
    agent any

    stages {
       node{
        stage('Build')
         {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') 
        {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy')
         {
            steps {
                echo 'Deploying....'
            }
        }
      }
    }
}
