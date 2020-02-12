@Library('shlib1')_
pipeline
{
    agent any
stages{
 stage('gitlab')
        {
            steps{
             commits()
             influx()

                 }
         }
        stage('contributors')
        {
            steps{
             contributors()
             influx()

                 }
         }
         }
         }
