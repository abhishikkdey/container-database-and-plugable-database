# container-database-and-plugable-database
container database and pluggable database configuration

## command to create pluggable database from pdb$seed
"SQL> create pluggable database prod_pdb2 admin user
  2  pdbadmin identified by prod2
  3  FILE_NAME_CONVERT=('/u01/app/oracle/oradata/PROD/pdbseed/','/u01/app/oracle/oradata/PROD/prod_pdb2/');
"
