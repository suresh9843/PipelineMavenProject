pipeline 
{ 
    agent any 
     tools { 
        maven 'maven-3.6' 
        jdk 'java-1.8' 
    }
    stages 
	{
	stage('Build') 
	  {
            steps 
        	{  
	        bat 'mvn clean'
               }
          }
	/*	
	  stage('Checking Echo') 
	  {
            steps 
        	{  
	        echo 'This is my first stage '
               }
          }
		
	stage ('Print Env Variables')
	{
            steps 
	     {
		script
		     {
			if (isUnix()) {
			    echo 'This is a unix box, so your script should use sh command for executing steps'
			    sh env
			}
			else {
				echo 'This is a Windows box, so your script should use bat command for executing steps'
			    bat "set"  // this prints the all the environment variables
			}
		     }
		 // The bat is command equalent to sh in unix, so wherever u use sh command in unix box u should replace with bat in windows    		 
                bat 'echo "single line command execution' // 
		bat '''
                     echo 'Multiline command execution 1'
                     echo 'Multiline command execution 2'
                    '''
		     
		     
             }
        }
	
       stage("Checking Maven, Java Versions")
       {
	       steps {
		       bat 'mvn --version'
		       bat 'java -version'
	       }
	       
       }		
	*/
        
		
    }
}
