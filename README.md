# Incidentes de Seguridad en Chile

Este es un listado de incidentes de seguridad informática en empresas de alto perfil en Chile, mantenido por la comunidad a partir de la información públicamente accesible en medios de prensa y redes sociales. 

# Incidentes

## 25 de Julio de 2018 - ¿Correos de Chile?

- **Falla**: Filtración de datos de 14 mil tarjetas de crédito, 2.446 de ellas estaban vigentes.

- **Impacto**: Los datos contienen toda la información necesaria para realizar una compra.

- **Reportado por**: Fernando Lagos (@Zerial en Twitter)

- **¿Hubo recompensa ("bug bounty") o reconocimiento para quien lo reportó?** No. ⚠️

- **Comunicado oficial de la empresa**: Correos de Chile confirma que la filtración de números de tarjetas "no tendría relación con los sistemas de Correos".  Esto, tras hacer "los análisis y revisiones pertinentes en un trabajo conjunto con el proveedor externo". ⚠️

- Fuentes: 
  - [Segundo comunicado acerca del incidente de seguridad de tarjetas de crédito(SBIF)](www.sbif.cl/sbifweb/servlet/Noticia?indice=2.1&idContenido=12161)
  - [Correos de Chile investiga posible filtración de datos de tarjetas desde su servicio de casillas](https://www.fayerwayer.com/2018/07/correos-de-chile-filtracion/)
  - [Correos de Chile tras revisión por filtración determina que esta no tendría relación con sus sistemas (actualizado)](https://www.latercera.com/pulso/noticia/correos-chile-declara-se-encuentra-investigando-la-posible-filtracion-datos/258029/#)

## 2 de Agosto de 2018 - Banco Falabella

- **Falla**: Fue posible ingresar a la cuenta de clientes sin conocer su contraseña. Bastaba ingresar espacios. 

- **Impacto**: Posible fuga de información personal de clientes.

- **Reportado por**: Quien lo descubrió prefirió proteger su identidad para evitar problemas legales. No existen canales oficiales para reportar problemas de seguridad en BancoFalabella. ⚠️

- **¿Hubo recompensa ("bug bounty") o reconocimiento para quien lo reportó?** No. ⚠️

- **Comunicado oficial de la empresa**: Ninguno. ⚠️

- Fuentes: 
  - [Banco Falabella permitió acceder a las cuentas bancarias sin contraseña
](https://ohmygeek.net/2018/08/02/banco-falabella-falla-acceso/)
  - [Qué sabemos de la falla de seguridad de Banco Falabella, un día después](https://ohmygeek.net/2018/08/03/que-sabemos-falla-banco-falabella/)


# Simbología

El signo ⚠️ apunta a un comportamiento alejado de las buenas prácticas de seguridad de la empresa afectada. Los comportamientos destacados con ese signo son:

- Poner en problemas legales a quien reporta una falla de seguridad después de haber sido descubierta (a) sin fines maliciosos y (b) habiendo hecho todos los esfuerzos esperables de un _responsible disclosure_. 

- No contar con canales para recibir reportes de problemas de seguridad.

- No reconocer y/o recompensar a quien descubrió y reportó el problema.

- No comunicar públicamente la situación junto a su mitigación y corrección.

# Contribuir

Para contribuir a este listado, simplemente envía un pull request que modifique este README. Debes seguir el mismo patrón existente para agregar nuevos incidentes (y debes incluir cada incidente en un pull request separado). También son bienvenidas actualizaciones o correcciones en cada reporte, así como también mejoras en el formato y simbología. Todo en issues o pull requests separados 😉

Los hechos descritos en cada reporte de incidente deben estar completamente respaldados por las fuentes citadas. 
