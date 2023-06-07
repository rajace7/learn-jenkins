pipeline
{
 agent
 {
    node
    {
    label 'rajesh_workstation'
    }
 }
  enviornment
  {
    env_var = "dev.example.com"
  }
  stages
  {
    stage('one')
    {
        steps
        {
            sh 'echo hello world'
            sh 'echo ${env_var}'
        }

    }
  }
   post
      {
          always
          {
               sh 'echo post steps'
          }
      }
}