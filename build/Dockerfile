FROM jenkins/jenkins:lts

USER root
COPY plugins.txt ${JENKINS_HOME}/plugins.txt
USER jenkins
RUN /bin/jenkins-plugin-cli --verbose --plugin-file ${JENKINS_HOME}/plugins.txt

