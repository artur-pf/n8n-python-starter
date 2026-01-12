ARG N8N_VERSION=latest
FROM n8nio/runners:latest

USER root
RUN cd /opt/runners/task-runner-python && uv pip install numpy pandas matplotlib polars plotly
COPY n8n-task-runners.json /etc/n8n-task-runners.json
USER runner

