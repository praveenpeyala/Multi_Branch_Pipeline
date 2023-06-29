node('master') 
{
    stage('Job - main-2.O branch') 
    {
        echo 'Hello Mr. Praveen....Welcome to my World-2.O !!!'
    }
}

node('master')
{
    stage('S1-Cont. Downld - Calcwebapp-Project')
    {
        git 'https://github.com/praveenpeyala/calcwebapp.git'
    }
}

node('master')
{
    stage('S2-Cont. Build')
    {
        sh 'mvn clean package'
    }
}
