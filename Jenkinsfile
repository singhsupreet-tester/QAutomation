pipeline
{
    agent any
    
    stages 
    {
        stage("Build")
        {
            steps
            {
                echo("Build Project")
            }
        }
        
        
        stage("Run UTS")
        {
            steps
            {
                echo("Run Unit Test Cases")
            }
        }
        
        stage("Deploy to DEV")
        {
            steps
            {
                echo("DEV Deployment")
            }
        }
        
        stage("Deploy to QA")
        {
            steps
            {
                echo("QA Deployment")
            }
        }
        
        stage("Run Automation Regression Test")
        {
            steps
            {
                echo("Running Regression Automation Test Cases")
            }
        }
        
        stage("Deploy to STAGE")
        {
            steps
            {
                echo("Deploy to Stage Environment")
            }
        }
        
        
         stage("Run Sanity Automation Test")
        {
            steps
            {
                echo("Run Sanity Automation Test Cases")
            }
        }
        
         stage("Deploy to PROD")
        {
            steps
            {
                echo("Deploy to Prod Environment")
            }
        }
        
        
        
    }
    
}