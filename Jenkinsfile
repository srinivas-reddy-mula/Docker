node('docker')
{
    stage('Git')
    {
        git 'https://github.com/srinivas-reddy-mula/Docker.git'
    }
    stage('install docker')
    {
    sh 'pwd'
    sh 'whoami'
    sh 'docker_install.sh'
    sh 'sudo usermod -aG docker jenkins'
    }
}
