pipeline{

    agent any 

    stages{

        stages('Git Checkout'){

            steps{

                script{
                 
                 git branch: 'main', url: 'https://github.com/vikash-kumar01/Counter_application.git'

                }
            }
        }
    }
}