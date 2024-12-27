@Library('devops-jenkins-shared-library@ojt-cloud') _

def COLOR_MAP = ['SUCCESS': 'good', 'FAILURE': 'danger', 'UNSTABLE': 'danger', 'ABORTED': 'danger']
def gitbranch = "${env.BRANCH_NAME}"

HiyaPipeline(gitbranch:"${gitbranch}")
