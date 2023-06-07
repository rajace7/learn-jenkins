pipeline
{
 agent
 {
    node
    {
    label 'rajesh_workstation'
    }
 }
  stages
  {
    stage('one')
    {
        steps
        {
            sh 'echo hello world'
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