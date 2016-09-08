FROM cassandra:2

ENV CASSANDRA_CONFIG /etc/cassandra
ADD scripts/config-cassandra /usr/local/bin/config-cassandra
RUN /usr/local/bin/config-cassandra
RUN rm -f /etc/security/limits.d/cassandra.conf
