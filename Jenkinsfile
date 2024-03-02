pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/amanbaghel101/"
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
