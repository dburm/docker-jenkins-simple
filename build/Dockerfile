FROM jenkins/jenkins:lts

ENV CASC_JENKINS_CONFIG=${JENKINS_HOME}/casc

COPY plugins.txt ${JENKINS_HOME}/plugins.txt
RUN /bin/jenkins-plugin-cli --verbose --plugin-file ${JENKINS_HOME}/plugins.txt
