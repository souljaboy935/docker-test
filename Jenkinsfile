pipeline{
    agent { label 'master' }
        stages{
            stage('pull_docker_image'){
                steps{
                    sh 'sudo docker pull souljaboy935/upload:jenkins'
                }
            }
            stage('run_container'){
                steps{
                    sh 'sudo docker run souljaboy935/upload:jenkins'
                    echo 'this worked'
                }
            }
        }
}
