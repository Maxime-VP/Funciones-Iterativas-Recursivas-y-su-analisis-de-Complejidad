# Act 1.1 - Funciones Iterativas, Recursivas y su análisis de Complejidad
<table style="width: 100%; border-collapse: collapse; background-color: rgb(241, 241, 241); margin-bottom: 20px;" border="0" cellspacing="0" cellpadding="10">
<tbody>
<tr>
<td style="width: 100%;">
##¿Qué tengo que hacer?<br>
Realiza una aplicación en C++ en <span style="text-decoration-line: underline;">forma individual</span>,&nbsp; que calculé la sumatora de **1 hasta n** y llame a tres funciones:
<table style="height: 10px; width: 0%; border-collapse: collapse; border-top-style: solid; border-right-style: solid; border-bottom-style: solid; border-left-style: solid;" border="1">
<tbody>
<tr style="height: 24px;">
<td style="width: 30%; height: 10px; background-color: rgb(25, 99, 169);" rowspan="5"><span style="font-size: 18pt; color: rgb(255, 255, 255);">sumaIterativa</span></td>
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Descripción</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">
Calcule la sumatoria de 1 hasta n con un metodo iterativo.
</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Entrada</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">Un entero positivo (n)</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Salida</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">La sumatoria de 1 hasta n</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);"><span style="color: rgb(0, 0, 0);">Precondición</span></td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);"><span style="color: rgb(0, 0, 0);">n es un entero positivo</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 10px; background-color: rgb(0, 139, 247);"><span style="color: rgb(0, 0, 0);">Postcondición</span></td>
<td style="width: 0px; height: 10px; background-color: rgb(183, 219, 255);"><span style="color: rgb(0, 0, 0);">Nada</span></td>
</tr>
</tbody>
</table>
<br>
<table style="height: 10px; width: 0%; border-collapse: collapse; border-top-style: solid; border-right-style: solid; border-bottom-style: solid; border-left-style: solid;" border="1">
<tbody>
<tr style="height: 24px;">
<td style="width: 30%; height: 10px; background-color: rgb(25, 99, 169);" rowspan="5"><span style="font-size: 18pt; color: rgb(255, 255, 255);">sumaRecursiva</span></td>
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Descripción</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">


Calcule la sumatoria de 1 hasta n con un metodo recursivo.
</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Entrada</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">Un entero positivo (n)</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Salida</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">La sumatoria de 1 hasta n</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);"><span style="color: rgb(0, 0, 0);">Precondición</span></td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);"><span style="color: rgb(0, 0, 0);">n es un entero positivo</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 10px; background-color: rgb(0, 139, 247);"><span style="color: rgb(0, 0, 0);">Postcondición</span></td>
<td style="width: 0px; height: 10px; background-color: rgb(183, 219, 255);"><span style="color: rgb(0, 0, 0);">Nada</span></td>
</tr>
</tbody>
</table>
<br>
<table style="height: 10px; width: 0%; border-collapse: collapse; border-top-style: solid; border-right-style: solid; border-bottom-style: solid; border-left-style: solid;" border="1">
<tbody>
<tr style="height: 24px;">
<td style="width: 30%; height: 10px; background-color: rgb(25, 99, 169);" rowspan="5"><span style="font-size: 18pt; color: rgb(255, 255, 255);">sumaDirecta</span></td>
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Descripción</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">
Calcule la sumatoria de 1 hasta n con un metodo matemático directo.
</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Entrada</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">Un entero positivo (n)</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);">Salida</td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);">La sumatoria de 1 hasta n</td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 0px; background-color: rgb(0, 139, 247);"><span style="color: rgb(0, 0, 0);">Precondición</span></td>
<td style="width: 0px; height: 0px; background-color: rgb(183, 219, 255);"><span style="color: rgb(0, 0, 0);">n es un entero positivo</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 0px; height: 10px; background-color: rgb(0, 139, 247);"><span style="color: rgb(0, 0, 0);">Postcondición</span></td>
<td style="width: 0px; height: 10px; background-color: rgb(183, 219, 255);"><span style="color: rgb(0, 0, 0);">Nada</span></td>
</tr>
</tbody>
</table>
<br>Todas las funcionalidades deberán de estar correctamente alineadas y documentadas.&nbsp; Recuerda que todas las funcionalidades deberán pasar exitosamente todas las pruebas. Como parte de la documentación deberá incluirse la complejidad de cada una de ellas.
<table style="width: 100%; border-collapse: collapse; background-color: rgb(241, 241, 241); margin-bottom: 20px;" border="0" cellspacing="0" cellpadding="10">
<tbody>
<tr>
<td style="width: 100%;">
## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **70%** - Para cada una de las funcionalidades se evaluará:
        
    - **Excelente (70%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (55%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (40%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (25%)** - pasa correctamente menos del 50% de los casos de prueba.
    

- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](https://experiencia21.tec.mx/courses/74123/files/16199560/download?wrap=1 "Estandar Programacion.pdf")</span>
- **10%** - Se respetenan los nombres de las funciones en la aplicación.
- **10%** - Especifican en cada uno de las funcionalidades **la complejidad computacional** como parte de su documentación.

</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>

&nbsp;

<table style="width: 100%; border-collapse: collapse; background-color: rgb(241, 241, 241); margin-bottom: 20px;" border="0" cellspacing="0" cellpadding="10">
<tbody>
<tr>
<td style="width: 100%;">
## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Entrega los archivos correspondientes de la actividad, en la sección correspondiente dentro de esta plataforma.
</td>
</tr>
</tbody>
</table>

