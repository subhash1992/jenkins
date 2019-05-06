pipeline {
    agent any
    stages {
        stage ("monitor") {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                  sh 'for n in `seq 1 10`; do echo $n; sleep 1; done'    
                }
            }
        }
    }
}
