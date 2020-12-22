FROM alpine:latest
RUN apk --update add postgresql-client
RUN mkdir sqls
COPY OpenELIS_base.sql /sqls/OpenELIS_base.sql
ENTRYPOINT ["psql"]
