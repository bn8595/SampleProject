def workspace;
node
{
    stage('CheckOut')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '3ace367b-7f98-4e6c-9b22-d659b724e324', url: 'https://github.com/bn8595/SampleProject.git']]])
        workspace =pwd()
    }
    stage('Static Code Analysis')
    {
        echo "Static Code Analysis"
    }
    stage ('Unit Testing')
    {
        echo "Unit Testing"
    }
    stage ('Build')
    {
        echo "Build"
    }
    stage ('Delivery')
    {
        echo "Delivery"
    }
    
}
