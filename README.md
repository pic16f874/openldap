
docker-compose -f openldap.yml up

docker-compose -f openldap.yml down
docker volume rm openldap_ldap_config openldap_ldap_database


