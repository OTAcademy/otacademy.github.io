# How to set up webservice login for local testing with ZnoteAAC and XAMPP
this tutorial assumes that you already have a databse for your tfs

1. delete everything from /xampp/htdocs/ directory

2. Go to ZnoteAAC, to v2 branch on GitHub:
https://github.com/Znote/ZnoteAAC/tree/v2

3. code -> download zip

4. unzip everything, it should look like this:
[]()

5. open config.php

6. configure your mysql connection and webservice
(optional: if you do not want to configure PHP caching, you can set `'memory' => false`)

[]()
[]()

7. open login.php if you want to personalize it

8. start apache and mysql from xampp control panel

9. open http://localhost/phpmyadmin in browser

10. click on tfs database

11. click "import" on top bar

12. choose /htdocs/engine/database/znote_schema.sql and confirm with "import" button

13. restart your apache
