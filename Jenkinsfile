node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/AbdulMuq1990/Multibranchpipeline.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
