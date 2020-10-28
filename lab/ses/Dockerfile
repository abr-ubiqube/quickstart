FROM ubiqube/msa-api:2.1.0rc2

#RUN usermod -u 1000 ncuser
#RUN groupmod -g 1000 ncuser

RUN \
	chkconfig ubi-base off		;\
	chkconfig postgresql-9.3 off	;\
	chkconfig elasticsearch off	;\
	chkconfig kibana off		;\
	chkconfig ubi-sms off		;\
	chkconfig ubi-webconf off ;\
	chkconfig ubi-ztd off ;\
	:

RUN rm -rf /opt/fmc_repository/CommandDefinition/Reference /opt/fmc_repository/CommandDefinition/.meta_Reference