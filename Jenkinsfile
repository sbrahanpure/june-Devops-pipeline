pipeline
{
  agent any
  stages
   { 
   stage ('Git clone')
    { steps 
       { sh 'echo downloading the code' }
     }
      
    stage ('Code Compile')
      { steps
         { sh 'echo code is compiling' }
      }
    
     stage ('Get Approval Status')
     { input "Please approve for the deployement process" }
     
     stage ('Deploe Code')
      { steps
         { sh 'echo code is Deploying' }
      } 
    }
  }
