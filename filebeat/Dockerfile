FROM docker.elastic.co/beats/filebeat:7.11.2

COPY config/filebeat.yml /usr/share/filebeat/
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
RUN chmod go-w /usr/share/filebeat/filebeat.yml
