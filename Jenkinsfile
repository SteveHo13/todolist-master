pipeline {
     agent any
     stages {
        stage("Build") {
            steps {
                sh "npm install"
                //sh "npm run build"
                 sh "npm start"
            }
        }
        stage("Deploy") {
            steps {
                 echo "Deploy"
                //sh "sudo rm -rf /var/www/jenkins-react-app"
                //sh "sudo cp -r ${WORKSPACE}/build/ /var/www/jenkins-react-app/"
            }
        }
    }
}
