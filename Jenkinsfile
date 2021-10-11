pipeline{
    agent { label 'master' }
        stages{
            stage('pull_docker_image'){
                steps{
                    sh 'docker pull souljaboy935/upload:jenkins'
                }
            }
            stage('run_container'){
                steps{
                    sh 'docker run souljaboy935/upload:jenkins'
                    echo 'this worked'
                }
            }
        }
}
