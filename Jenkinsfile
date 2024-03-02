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
        sh "java Demo.java"
      }
    }
  }
}
