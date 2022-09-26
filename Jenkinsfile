pipeline{
agent any
stages {
        stage('Test')
    {
        sh'echo Vijay anand'
    }
stage ('declarative Script Sample Pipeline')
agent {label 'Label_Maven_3.6.3'}
steps{
git url: 'https://github.com/Vijay722113/spring-petclinic.git'
branch:main
sh 'mvn package'

}

}

}