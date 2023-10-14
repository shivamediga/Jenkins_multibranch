node('built-in') 
{
    stage('Continuous DownloadMaster') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous BuildMaster`') 
	{
    sh label: '', script: 'mvn package'
	}
}
