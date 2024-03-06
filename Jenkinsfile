pipeline
{
    agent any
    tools
    {
        maven 'M2_HOME'
    }
     stages
     {
          stage("checkout")
          {
              steps
              {
                  git 'https://github.com/SriDevops-T/EcommWeb.git'
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
