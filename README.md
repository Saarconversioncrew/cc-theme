**get module, including fields, created in Design manager:**

cd modules
hs fetch --overwrite /website_theme/modules/module-name.module/ module-name.module/


**automatically update files to HubSpot:**

cd .
hs watch --remove website-theme \website-theme