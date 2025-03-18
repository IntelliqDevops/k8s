pipeline
{
    agent any
    stages
    {
        stage('Run java code')
        {
            steps
            {
                git 'https://github.com/IntelliqDevops/maven.git'
            }
        }
         stage('Build java code')
        {
            steps
            {
               sh 'mvn package'
            }
        }
    }
}
