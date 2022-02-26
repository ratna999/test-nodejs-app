pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy  to application") { 
         steps { 
           sh 'echo "deploying THE application..."'
         }

     }
  
   	}

   }
