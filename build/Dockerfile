FROM jenkins/jenkins:lts

COPY plugins.txt ${JENKINS_HOME}/plugins.txt
RUN /bin/jenkins-plugin-cli --verbose --plugin-file ${JENKINS_HOME}/plugins.txt

