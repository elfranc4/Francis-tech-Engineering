pipeline{
    agent any
    stages{
        stage(1'-clonecode'){
            steps{
                sh 'df -h'
            }
        }
        stage('2-memorycheck'){
            steps{
                sh 'free -g'
            }
        }
        stage('3-welcomepage'){

            echo "welcome to Jenkins"
        }
    }
    stage('4-francis-check'){
        steps{
            
        }
    }
     stage(5-dwoncheck){
        steps{
            sh 'cat /etc/os-release'
        }

     }       

}