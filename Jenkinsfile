node('master') 
{
    stage('Job - main-1.O branch') 
    {
        echo 'Hello Mr. Praveen....Welcome to my World-1.O !!!'
    }
}

node('master')
{
    stage('S1-Cont. Downld - Prvn-WAR-file-Project')
    {
        git 'https://github.com/praveenpeyala/Prvn-WAR-file.git'
    }
}

node('master')
{
    stage('S2-Cont. Build')
    {
        sh 'mvn clean package'
    }
}
