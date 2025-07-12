pipeline{
    agent any
    stages{
        stage('print HTML'){
            steps{
                script {
                    def htmlContent = readFile('index.html')
                    echo "HTML Content: ${htmlContent}"
                }
            }
        }
    }
}