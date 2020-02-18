pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                changeset pattern: "WORLD.js", caseSensitive: ture
            }
            steps{
                echo "Hello World changeset JS"
            }
        }
    }
}
