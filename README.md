# docker-openldap-phpldapadmin

---

For initial groups and users, run the following command.
ldapadd -x -D "cn=admin,dc=example,dc=org" -w admin -H ldap://localhost -f sample.ldif

$ cat .env<br>
LDAP_ORGANISATION=4wxyz<br>
LDAP_DOMAIN=4wxyz.com<br>
LDAP_ADMIN_PASSWORD=YourPassWord<br>

---

Login DN: cn=admin,dc=4wxyz,dc=com<br>
Password: YourPassWord<br>
