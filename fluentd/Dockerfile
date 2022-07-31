FROM fluent/fluentd:latest
USER root
RUN fluent-gem install fluent-plugin-elasticsearch && \
    fluent-gem install fluent-plugin-slack && \
    fluent-gem install fluent-plugin-grep
USER fluent