pipeline{
    
    environment {
        NEW_VERSION = '2.3.0'
    }
    
    parameters{
        choice(name: 'vchoice', choices: ['1','2','3'])
    }

    agent any

    stages{

        stage("build"){
            steps{
                echo "buiding app"
                echo "version is ${NEW_VERSION}"
            }
        }
        
        stage("test"){
            steps{
                echo "testing app"
                echo "vchoice is ${params.vchoice}"
            }
        }

    }
  
}
