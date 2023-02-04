node('built-in') 
{
    stage('Continuous Download_blaster') 
	{
    git 'https://github.com/Prakashkuvvam/multibranch.git'
	}
    stage('Continuous Build_blaster') 
	{
    sh label: '', script: 'mvn package'
	}
}
