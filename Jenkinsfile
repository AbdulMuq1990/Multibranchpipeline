node('built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/AbdulMuq1990/Multibranchpipeline.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
