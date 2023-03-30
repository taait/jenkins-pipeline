# Jenkins Pipeline

Jenkinsfile0
 stage 1
 agent is any

Jenkinsfile1
 stage 1-2-3
 stage names Build, Test, Deploy
 echo "Start of Stage ..."
 echo "Progress of Stage ..."
 echo "End of Stage ..."
 agent is any

Jenkinsfile2
 stage 1-2-3
 run sh python --version
 agent is docker container(img)

Jenkinsfile3
 stage 1-2-3-4
 used enviroments variables
 agent is any
