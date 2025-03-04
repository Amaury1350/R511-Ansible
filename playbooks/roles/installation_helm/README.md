Nom du rôle deploiement_site
===========

Déploiement d'un site web avec Ansible.

Prérequis
---------

Les prérequis qui ne sont pas couverts par Ansible ou le rôle doivent être mentionnés ici. Par exemple, si le rôle utilise le module EC2, il peut être utile de mentionner que le package boto est requis.

Variables du rôle
-----------------

Une description des variables configurables pour ce rôle doit être incluse ici, y compris les variables dans defaults/main.yml, vars/main.yml, et toutes les variables qui peuvent/doivent être définies via des paramètres pour le rôle. Toute variable lue à partir d'autres rôles et/ou de la portée globale (par exemple, hostvars, group vars, etc.) doit également être mentionnée ici.

Dépendances
-----------

Une liste des autres rôles hébergés sur Galaxy doit être incluse ici, ainsi que tous les détails concernant les paramètres qui peuvent devoir être définis pour d'autres rôles, ou les variables utilisées par d'autres rôles.

Exemple de Playbook
--------------------

Inclure un exemple de la façon d'utiliser votre rôle (par exemple, avec des variables passées en tant que paramètres) est toujours utile pour les utilisateurs :

  - hosts: serveurs
    roles:
     - { role: deploiement_site, x: 42 }

Licence
-------

BSD

Informations sur l'auteur
--------------------------

Une section optionnelle pour que les auteurs du rôle incluent des informations de contact ou un site web (HTML non autorisé).

