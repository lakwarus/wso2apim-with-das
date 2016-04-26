FROM dockerhub.private.wso2.com/wso2am:1.10.0

COPY artifacts/mysql-connector-java-5.1.34-bin.jar /mnt/wso2/carbon-home/repository/components/lib/
COPY apim/api-manager.xml /mnt/wso2/carbon-home/repository/conf/
COPY apim/master-datasources.xml /mnt/wso2/carbon-home/repository/conf/datasources/
COPY apim/registry.xml /mnt/wso2/carbon-home/repository/conf/
COPY apim/user-mgt.xml /mnt/wso2/carbon-home/repository/conf/
COPY apim/axis2.xml /mnt/wso2/carbon-home/repository/conf/axis2/
COPY apim/_AuthorizeAPI_.xml /mnt/wso2/carbon-home/repository/deployment/server/synapse-configs/default/api/
COPY apim/_TokenAPI_.xml /mnt/wso2/carbon-home/repository/deployment/server/synapse-configs/default/api/
COPY apim/_RevokeAPI_.xml /mnt/wso2/carbon-home/repository/deployment/server/synapse-configs/default/api/
COPY apim/_UserInfoAPI_.xml /mnt/wso2/carbon-home/repository/deployment/server/synapse-configs/default/api/


EXPOSE 9763
EXPOSE 9443
EXPOSE 8280
EXPOSE 8243
EXPOSE 10397