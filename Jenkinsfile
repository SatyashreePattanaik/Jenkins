Pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/SatyashreePattanaik/Jenkins.git"
      }
    }
    stage("Run")
    {
      steps
      {
        sh "java demo.java"
        sh "python main.py"
      }
    }
  }
}
