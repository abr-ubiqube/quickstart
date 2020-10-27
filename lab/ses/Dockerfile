FROM ubiqube/msa-api:2.1.0rc2

ENV container docker

RUN chkconfig --del ubi-sms
RUN chkconfig --del ubi-webconf
RUN chkconfig --del ubi-ztd
RUN chkconfig --del postgresql-9.3

CMD [ "/sbin/init" ]
