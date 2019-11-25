pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
			
				script{
				
					//def name = "jeff"
					def name = "jon"
					
					if(name == "jeff")
						println("hi ${name}")
					else
                                        if(name != "jeff")
						println("hi human")				
												
					sleep 2	
					echo "end of script"
				}
            }
        }
    }
}
