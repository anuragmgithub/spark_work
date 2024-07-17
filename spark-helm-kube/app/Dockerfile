# spark-helm-kube/app/Dockerfile

FROM bitnami/spark:latest

COPY workout.py /opt/spark-apps/workout.py

ENTRYPOINT [ "/opt/bitnami/scripts/spark/entrypoint.sh" ]
