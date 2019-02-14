FROM quay.io/operator-framework/ansible-operator:v0.5.0

COPY roles/ ${HOME}/roles/
COPY playbook.yaml ${HOME}/playbook.yaml
COPY watches.yaml ${HOME}/watches.yaml

USER root
RUN pip install --no-cache-dir boto boto3 msrest msrestazure
