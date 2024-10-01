pipeline{
    agent any
    stages{
        stage('bulid-system details')
        {
            steps
            { 
                sh '''
                echo 'syestm details'
                uname -a
                '''
            }
        }
        stage('memory details')
        {
            steps
            { 
                sh '''
                echo 'memory details'
                free -h
                '''
            }
        }
    
        stage('cpu details')
        {
            steps
            { 
                sh '''
                echo 'cpu details'
                lscpu
                '''
            }
        }
        stage('date')
        {
            steps
            { 
                sh '''
                echo 'date'
                date
                uptime
                '''
            }
        }
    }
}
