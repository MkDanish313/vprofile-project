pipeline { 
	agent any	
	tools {
        maven "maven3"
        jdk "OracleJDK8"
    }

	
    stages{
        
        stage('BUILD'){
            steps {
                sh 'mvn  install -DskipTests'
            }   
        }
    }
}
