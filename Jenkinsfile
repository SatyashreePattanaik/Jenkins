pipeline {
    agent {
	    label 's1'
    }

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/SanjeevaSomisetti49/pipeline_project.git'
                sh "python3 main.py"
		        sh "java Demo.java"
            }
        }
    }
}
      
      
