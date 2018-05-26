# ServiceClientSetup
Sample to overwrite Efactura Uy Service

se pasan las credenciales del webservice de factura a una dll native ServiceCloentSetup
Esta recibe los parametros y los sobreescribe en el request. 
Es una extension de la funcionalidad del tipo de datos location 

Como paritcularidad en certificado del cliente se pasa como un array de bytes encodeado en base 64 con el contenido del certificado desde el fuente genexus y se recibe en la dll que lo carga en el keystore 
-
