pipeline
{
    agent any
    tools
    {
        maven 'maven'
    }
     stages
     {
          stage("checkout")
          {
              steps
              {
                  git 'https://github.com/spring-projects/spring-petclinic'
                  echo "repo downloaded successfully"
              }
          }
          stage("mvn-package")
          {
              steps
              {
              sh "mvn package"

              }
          }
     }
}
