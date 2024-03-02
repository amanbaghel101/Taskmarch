pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/amanbaghel101/Taskmarch.git"
      }
    }
    stage("Run")
    {
      steps
      {
        bat "java Demo.java"
      }
    }
  }
}
