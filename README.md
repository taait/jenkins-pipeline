# Jenkins Pipeline

Jenkinsfile0<br>
 stage 1<br>
 agent is any<br><br>

Jenkinsfile1<br>
 stage 1-2-3<br>
 stage names Build, Test, Deploy<br>
 echo "Start of Stage ..."<br>
 echo "Progress of Stage ..."<br>
 echo "End of Stage ..."<br>
 agent is any<br><br>

Jenkinsfile2<br>
 stage 1-2-3<br>
 run sh python --version<br>
 agent is docker container(img)<br><br>

Jenkinsfile3<br>
 stage 1-2-3-4<br>
 used enviroments variables<br>
 agent is any<br>
