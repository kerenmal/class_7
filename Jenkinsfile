properties([pipelineTriggers([pollSCM('* * * * * ')])])
node("test"){
    stage("clone"){
        git branch: 'main', url: 'https://github.com/kerenmal/class_7.git'

    }
    stage("execute"){
        bat "dir"
        bat "c:\\Users\\kmalikin\\AppData\\Local\\Programs\\Python\\Python39\\python main.py"
    }
}