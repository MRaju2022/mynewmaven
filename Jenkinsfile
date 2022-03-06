node {
    stage('continuousDownload:Loans')
    {
        git 'https://github.com/MRaju2022/maven.git'
    }
    stage('continuousBuild:Loans')
    {
        sh 'mvn package'
    }
   
}
