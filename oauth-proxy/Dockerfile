#
# Dockerfile for defining the oauth proxy
#
FROM  bitnami/oauth2-proxy:latest 

COPY ./oauth2_proxy.cfg /etc/

#ENV OAUTH2_PROXY_CLIENT_ID
#ENV OAUTH2_PROXY_CLIENT_SECRET

WORKDIR /opt/bitnami/oauth2-proxy
USER 1001
ENTRYPOINT [ "oauth2_proxy" ]
CMD ["-config=/etc/oauth2_proxy.cfg"]
