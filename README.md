# sesion7-tarea-individual
# Exercicis tractament de dades
1.- Amb la BBDD Jardineria facilitada, crea i executa un script “actualitza.sql” que realitce les
següents accions.
1. Inclou una oficina amb seu a Fuenlabrada.
2. Inclou un empleat per a l’oficina de Fuenlabrada que sigui representant de
vendes.
3. Incluo un client del representant de vendes creat a l’anterior punt.
4. Inclou una comanda (pedido) del client anterior (amb el seu detall) d’almenys
dos productes amb una transacció.
5. Actualitza el codi del cliient inserit i consulta si hi ha canvits a les taules
relacionades.
6. Borra el client i verifica si hi ha canvits.

2.- Realitza les següents accions:
1. Borrar els clients que no tinguen comandes.
2. Decrementa en un 20% el preu dels productes que no tinguen comandes.
3. Esborra els pagaments del client amb menor límit de crèdit.
4. Establir a 0 el límit de crèdit del client que menys unitats demanades tingui del
producte `OR-179'.Borra los pagos del cliente con menor límite de crédito.

3.- Realiza las siguientes acciones:
1. Borra el cliente que menor limite de crédito tenga. ¿Es posible borrarlo sólo
con una consulta?
2. Modifica la taula “DetallePedidos” per a inserir un camp numèric anomenat
IVA. Mitjançant una transacció, estableix el valor d'aquest camp a 18 per a
aquells registres la comanda dels quals tingui data a partir de Juliol de 2010. A
continuació actualitza la resta de Comandes establint al 16 l'IVA.
3. Modifica la taula “DetallePedidos” per a incorporar un camp numèric
anomenat “TotalLinea” i actualitza tots els seus registres per a calcular el seu
valor amb la fórmula “TotalLinea=PrecioUnidad*Cantidad*IVA/100”.
4. Esborra el client que menor limiti de crèdit tingui. És possible esborrar-ho
només amb una consulta?
