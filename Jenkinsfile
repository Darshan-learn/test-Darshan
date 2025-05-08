pipeline
{
agent any
tools
{
    jdk "java-11"
    maven "maven"
}
stages{
    stage('git checkout'){
        steps{
            git branch: 'main', url: 'https://github.com/Darshan-learn/test-Darshan.git'
        }
    }
    stage('compile'){
        steps{
            sh "mvn complie"
        } 
        }
        stage('build'){
        steps{
            sh "mvn package"
    }
        }
    }
    }

    
    