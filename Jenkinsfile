pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh '/home/jenkins/maven/latest/mvn clean compile'
                }
            }
        

        stage ('Testing Stage') {

            steps {
                
                    sh '/home/jenkins/maven/latest/bin/mvn test'
                }
            }



        stage ('Deployment Stage') {
            steps {
        
                    sh '/home/jenkins/maven/latest/mvn deploy'
                }
            }
        }
    }

