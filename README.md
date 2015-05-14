WebYo.es Symfony2.3 Distribution
============

Initial configuration/structure of Symfony2.3 project with:
- SonataUserBundle
- SonataAdminBundle
- BraincraftedBootstrapBundle


After that you have to create username to access the dashboard and give him proper credentials role - ROLE_SONATA_ADMIN :

    php app/console fos:user:create
    php app/console fos:user:promote

