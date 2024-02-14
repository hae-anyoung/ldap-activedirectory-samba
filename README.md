# ldap-activedirectory-samba
Run Active Directory with Samba Server in Docker Container.

Run Via Docker Compose in single command

`docker compose up --build -d`

You can use [LDAP Admin](https://sourceforge.net/projects/ldapadmin/) to browse and modify the controller.
Or you can use [`samba-tool`](https://www.samba.org/samba/docs/current/man-html/samba-tool.8.html) as a CLI administration tool.

* Port: 389
* TLS is disabled
* USERNAME: `STTX-LOCAL\Administrator`
* Password: `admin123!`
* Distinguished Name: `DC=sttx,DC=local`

Reference : This is based following Article, I have made some refinements : https://schneide.blog/2022/06/27/running-a-containerized-activedirectory-for-developers/