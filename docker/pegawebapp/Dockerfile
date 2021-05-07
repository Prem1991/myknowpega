FROM pegasystems/pega-ready


COPY --chown=pegauser:root /prweb ${CATALINA_HOME}/webapps/prweb
RUN chmod -R g+rw   ${CATALINA_HOME}/webapps/prweb

COPY --chown=pegauser:root postgresql-42.2.20.jar ${CATALINA_HOME}/lib/