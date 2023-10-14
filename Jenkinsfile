node('built-in') 
{
    stage('Continuous DownloadLoans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous BuildLoans') 
	{
    sh label: '', script: 'mvn package'
	}
    }

