pipeline 
{ 
agent any
stages 
{
  stage ("Fetch Gitrepo")
{
    steps
    {
      scripts
      {
         git branch: 'Deployment', credentialsId: 'cfccf204-8eac-4ecf-aa10-43795871d80c', url: 'https://github.com/Balu118/Dockerfiles.git'
        }
        }
      }
  }
}
