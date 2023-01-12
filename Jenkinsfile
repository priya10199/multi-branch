pipeline {

         agent {
		 
		         label {
				         label 'built-in'
						 customWorkspace '/mnt/myproject'
				 }
		 
		 }
		 
		 stages {
		 
		          stage ('deploy') {
				  
                     				                 steps { 
									    
								            echo "Hello this is master branch"
								 }
				  }
				  
				  
				    stage ('start') {
				  
				                 steps {
								            sh "mkdir test"
								 }
				  }
		 }
}
