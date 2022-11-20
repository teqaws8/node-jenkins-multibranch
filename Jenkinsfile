pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
            sh 'sudo yum install nodejs npm --enablerepo=epel'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
