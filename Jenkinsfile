properties([parameters([string(defaultValue: 'Kfir', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("one"){
        git branch: 'main', url: 'https://github.com/kfiratar2/pycharm-repo.git'
        sh "cat 1.txt.txt"
        //bat "more 1.txt.txt"
    }
}
