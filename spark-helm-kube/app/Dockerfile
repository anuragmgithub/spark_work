# spark-helm-kube/app/Dockerfile

FROM bitnami/spark:latest

COPY wordcount.py /opt/spark-apps/wordcount.py

ENTRYPOINT [ "/opt/bitnami/scripts/spark/entrypoint.sh" ]
