@Library('shlib1')_
pipeline
{
    agent any
stages{
/* stage('commits')
        {
            steps{
             commits()
            // influx()

                 }
         }
        stage('contributors')
        {
            steps{
             contributors()
            // influx()

                 }
         }
     stage('issues')
        {
            steps{
             gitlab_issue()
            // influx()

                 }
         }
     stage('mergerequest')
        {
            steps{
             gitlab_mergerequest()
            // influx()

                 }
         }*/
    stage('user_commits'){
        steps{
            array_gitlab()
         }
         }
}
}
