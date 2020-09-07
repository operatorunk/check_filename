pipeline {
    agent {label 'windows_lumira'}
    stages {
        stage('build') {
            steps {
                script {
                    
                    echo "************** show file content *******************"
                    echo bat(returnStdout: true, script: 'C:\\Program Files\\Git\\mingw64\\etc && dir')
                    
                    
                }
            }
        }
    }
 
}
