# Arquitectura Gestión Documental
Propuesta de arquitectura para un sistema de gestión documental para industria manufacturera
Para el sistema de gestión documental se propone una arquitectura cliente servidor.
![Arquitectura](https://github.com/eisjgd2019/arqui_gestion_documental/blob/master/Arquitectura%20Cliente_servidor.jpg)
Y para la aplicación en arquitectura tres capas (capa de presentación, capa de negocio mediante servicios web, y capa de datos).  
![Arquitectura](https://github.com/eisjgd2019/arqui_gestion_documental/blob/master/Cliente-servidor.png)
# Justificación
Se determina implementar arquitectura cliente servidor como la que más se ajusta a la necesidad ya que el sistema de gestión documental será de uso interno y de pocos usuarios para un proceso secuencial y estandarizado, se hubiese podido proponer arquitectura SOA con bus de servicios pero debido a que este sistema no requiere interactuar no requiere interactuar con otros sistemas externos, ni tampoco aplica la arquitectura orientada a microservicios debido a que el sistema no tendrá trafico global (miles de transacciones).
