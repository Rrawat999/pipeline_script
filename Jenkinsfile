pipeline {
    agent any

    stages {
        stage('connect') {
            steps {
                echo 'connecting.. git remote add origin master "https://github.com/Rrawat999/script_check"'
            }
        }
        stage('pull') {
            steps {
                echo 'pulled.. git pull origin master'
            }
        }
        stage('Built') {
                    steps {
                echo 'build.. git add -A'
            }
        }
        stage('Commit') {
            steps {
                echo 'commiting.. git commit -m "modified"'
            }
        }
	stage('Deploy') {
            steps {
                echo 'Deploying.. git push origin master'
            }
        }
    }
}
