pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
			
				script{
				
					//def name = "Jeff"
					def name = "jon"
					
					if(name == "Jeff")
						println("Hi ${name}")
					else
                                        if(name != "Jeff")
						println("Hello human")				
												
					sleep 2	
					echo "End of script"
				}
            }
        }
    }
}
