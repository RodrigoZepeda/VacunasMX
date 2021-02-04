# VacunasMX
**Datos de las vacunas presentados en la conferencia de la SSA**

El archivo principal es [Registro_Vacunas.csv](https://github.com/RodrigoZepeda/VacunasMX/Registro_Vacunas.csv) el cual contiene las siguientes variables:

| **Variable**      | **Formato** | **Descripción**                                                            |
|-------------------|-------------|----------------------------------------------------------------------------|
| Fecha del reporte | d/m/y       | Fecha en la que la variable especificada fue anunciada en la vespertina    |
| Personal          | Caracter    | Población a la que fue aplicada la vacuna (ej: Personal de Salud)          |
| Cantidad          | Numérico    | Cantidad de individuos reportados (acumulados)                             |
| Dosis             | Entero      | Dosis de la vacuna (1 dosis = le falta el refuerzo; 2 dosis = ya completa) |
| Fuente            | Caracter    | Twitter / Youtube (de dónde salió el dato)                                 |
| Link              | Caracter    | URL de donde se obtuvo la información                                      |
| Nota              | Caracter    | Observaciones adicionales que pueden ser de utilidad para modelaje         |

## Errores de registro
Si encuentras un error en el registro por favor levanta un issue y pon el link del registro correcto .

## Información adicional
Si quieres agregar información adicional que no esté en la base pero sí se dé en las conferencias (por ejemplo, avance porcentual) agrega el histórico y arma un pull-request. Nosotros comenzaremos a agregar la nueva información de manera diaria a partir de eso. 
