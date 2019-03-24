FROM prom/prometheus
COPY prometheus.yml /etc/prometheus/prometheus.yml
COPY prod-targets.yml /etc/prometheus/prod-targets.yml
COPY jenkins-targets.yml /etc/prometheus/jenkins-targets.yml
COPY gerrit-targets.yml /etc/prometheus/gerrit-targets.yml
COPY zuul-targets.yml /etc/prometheus/zuul-targets.yml
