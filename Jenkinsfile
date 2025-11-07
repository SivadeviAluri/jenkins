pipeline {
    agent any
    stages {
        stage ('Build'){
            steps {
                echo "build stage"
            }
        }
        stage('groovystage'){
            steps{
                script{
                    //i want to definea variable
                    // def variablenam = "value"
                    def course = "k8s"
                    println("Thanks for enrolling to ${course}course")
                }
            }
        }
    }
     
}
