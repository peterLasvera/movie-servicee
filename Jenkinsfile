pipeline {
    agent any

    }
    stages {
        stage('Test') {
            }
            steps {
                echo "Docker Build JENKINS"

            }
        }
    }

    post{
        always{
            echo 'This for always notify'
        }
        success{
            echo 'notify success'
        }
        failure{
            echo 'notify failure'
        }
    }
}
