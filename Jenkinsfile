pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo '(change for git to commit 3) Build the code using a build automation tool to compile and package your code. Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit tests to ensure the code functions as expected and run integration tests to ensure the different components of the application work together as expected. Tool: JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Integrate a code analysis tool to analyse the code and ensure it meets industry standards. Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Perform a security scan on the code using a tool to identify any vulnerabilities. Tool: OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy the application to a staging server. Tool: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on the staging environment to ensure the application functions as expected in a production-like environment. Tool: JUnit'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy the application to a production server. Tool: AWS EC2'
            }
        }
    }
}