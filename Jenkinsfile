node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/hari1155/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	} 
          
}
