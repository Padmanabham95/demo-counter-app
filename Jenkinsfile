pipeline{

agent any

        stages{

            stage('Code Download'){

                steps{

                    git branch: 'main', url: 'https://github.com/Padmanabham95/demo-counter-app.git'

                }

            }
            stage('Unit Tests by Maven'){

                steps{

                    sh'mvn test'

                }

            }

        }

}