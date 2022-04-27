pipeline{
    
    environment {
        NEW_VERSION = '2.3.0'
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
            }
        }

    }
  
}
