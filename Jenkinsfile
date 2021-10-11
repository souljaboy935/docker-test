pipeline{
    agent('master'){
        stages{
            stage('pull docker image'){
                steps{
                    sh 'docker pull souljaboy935/upload:jenkins'
                }
            }
            stage('run container'){
                steps{
                    sh 'docker run souljaboy935/upload:jenkins'
                    echo 'this worked'
                }
            }
        }
    }
}
