pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                //withMaven(maven : 'maven_3_5_0') {
                    //sh 'mvn clean compile'
                sh 'echo Compile'
                //}
            }
        }

        stage ('Testing Stage') {

            steps {
                //withMaven(maven : 'maven_3_5_0') {
                  //  sh 'mvn test'
                sh 'echo test'
                //}
            }
        }


        stage ('Deployment Stage') {
            steps {
                //withMaven(maven : 'maven_3_5_0') {
                    //sh 'mvn deploy'
                sh 'echo Deploy'
                //}
            }
        }
    }
}
