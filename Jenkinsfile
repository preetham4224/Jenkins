pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh '/home/jenkins/maven/mvn clean compile'
                }
            }
        

        stage ('Testing Stage') {

            steps {
                
                    sh '/home/jenkins/maven/mvn test'
                }
            }



        stage ('Deployment Stage') {
            steps {
        
                    sh '/home/jenkins/maven/mvn deploy'
                }
            }
        }
    }

