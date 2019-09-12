FROM quay.io/operator-framework/ansible-operator:v0.10.0

USER root

RUN pip install -U passlib jmespath 

USER 1001

COPY watches.yaml ${HOME}/watches.yaml

COPY roles/ ${HOME}/roles/
