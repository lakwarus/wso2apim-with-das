FROM dockerhub.private.wso2.com/wso2das:3.0.1

COPY artifacts/mysql-connector-java-5.1.34-bin.jar /mnt/wso2/carbon-home/repository/components/lib/
COPY das/analytics-datasources.xml /mnt/wso2/carbon-home/repository/conf/datasources/
COPY das/API_Manager_Analytics_REST.car /mnt/wso2/carbon-home/repository/deployment/server/carbonapps/


EXPOSE 9763
EXPOSE 9443
EXPOSE 7611
EXPOSE 7711