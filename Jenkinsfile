pipeline
{
agent any
stages
      { ('stage-1')
       {    steps
        {      sh 'echo downloading code'

        } 
       }
      }


      { ('stage-2')
        { steps 
           { sh 'echo compiling code'
           }
        }
      }


      { ('stage-3')

        { steps
          { sh 'echo building'
          }
        }


      { ('stage-4')

        { steps
          { sh 'echo deploy'
          }
        }
      }
}
