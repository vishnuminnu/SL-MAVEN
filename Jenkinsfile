pipeline
{
	agent any
	    tools
	    {
		  maven 'MAVEN_HOME'
		
	    }
	    stages
	    {
		  stage('welcome stage')
		  {
			steps
			{
				echo 'welcome to pipeline'
			}
		  }
		  stage('clean stage')
		  {
			steps
			{
				bat 'mvn clean'
			}
		  }
		  stage('build stage')
		  {
			steps
			{
				bat 'mvn install'
			}
		  }
		  stage('finish stage')
		  {
			steps
			{
				echo 'finish stage'
			}
		  }
	    }
	
}