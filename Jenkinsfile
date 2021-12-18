pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout'
            }
        }
        stage('Build') {
            steps {
                echo 'Build'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
    }
post
{
always
{
echo 'always'
}
success
{
echo 'success'
}
failure
{
echo 'failure'
}
unstable
{
echo 'unstable'
}
changed
{
echo 'changed'
}
}
}
