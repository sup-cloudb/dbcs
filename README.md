# dbcs
insights de dbcs

> 1.  Antes de criar um DBCS, criar um software image com os One Offs listados no DOC ID 555.1:



![image](https://github.com/sup-cloudb/dbcs/assets/72585042/33efcfa5-c972-43e2-9036-91717e4ab0fa)




> Para verificarmos se ha patch de SO disponivel , executamos o comando abaixo e se Update Available = No, entao nao ha patch para aplicar.


[root@dbnorigin ~]# dbcli get-availableospatches

 Update Available     Reboot Required
 
 -------------------- --------------------`
 No                                       No

https://docs.oracle.com/pt-br/iaas/dbcs/doc/update-db-system-resources-using-dbcli.html
