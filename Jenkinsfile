pipeline {
    agent { 
        node {
            label 'my_pc'
            }
      }
     stages {
        stage('Build') {
            steps {
                echo "Building.."
                cd worldline
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                python hello.py
            }
        }
        stage('Deliver') {
            steps {
                echo "doing delivery stuff.."
            }
        }
    }
}