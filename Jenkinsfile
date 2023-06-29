node('master') 
{
    stage('Job - main branch') 
    {
        echo 'Hello Mr. Praveen....Welcome to my World !!!'
    }
}

node('master')
{
    stage('S1-Cont. Downld - Hello-world-Project')
    {
        git 'https://github.com/praveenpeyala/hello-world.git'
    }
}

node('master')
{
    stage('S2-Cont. Build')
    {
        sh 'mvn clean package'
    }
}
