pipeline
{
agent any
stages
      {
           stage ('build')
            { steps
             { echo 'building'}
            }
            
              stage ('complile')
            { steps
             { echo 'compling'}
            }
            
            stage ('test')
            { steps
             { echo 'testing'}
            }
            
             stage ('get approval')
            { steps
            { input "please approve the deployment?" }
            }
            
            stage ('deploy')
            { steps
             { echo 'code is deplyoing'}
            }
           
      }
}
