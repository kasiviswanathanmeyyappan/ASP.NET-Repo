pipeline {
 
    agent any

	stages {
	

	stage('Build'){

	steps{
         
		bat "\"${tool 'MSBuild'}\" aspnet4-sample.sln /p:Configuration=Debug /p:Platform=\"Any CPU\" /P:ProductVersion=1.0.0.${env.BUILD_NUMBER}"
	 
		
	 } 	 
      }
 
    }
 }
