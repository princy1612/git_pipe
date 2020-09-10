node
{
    stage("checkout scm")
    {
        echo("check the scm")
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '01', url: 'https://github.com/seleniumbase/SeleniumBase.git']]])
        
        echo("checked the scm")
        
    }
    stage ("build")
    {
        echo("build the  code")
    }
    stage ("test")
    {
       
        echo("test the code")
    }
}
