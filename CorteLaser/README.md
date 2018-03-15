# Corte Láser

*   [Tecnología](#tec)
*   [Preparación del archivo](#archivo)
*   [Uso de la máquina](#maquina)
*   [Seguridad](#seguridad)
*   [Materiales](#materiales)

<h2 id="tec">Tecnología</h2>

<h2 id="maquina">Uso de la máquina</h2>

- Encender la extracción de aire
- Encender el compresor de aire
- Encender la enfriadora de agua
- Encender la cortadora


- Importar el archivo DXF
- Revisar la colocación y el tamaño del diseño
- Revisar que no hay otras geometrías diferentes a lo que se quiere cortar
- Asignar colores a las estrategías diferentes. Los colores recomendados son:
	- Negro = Grabado (Por ahora no puede grabar) 
	- Verde = Marcado
	- Rojo = Corte interno
	- Cian = Corte interno 2
	- Azul = Corte externo
- Asignar los valores de potencia y velocidad para el material designado
- Enviar el corte a la láser


- Colocar y alinear el material
- Enfocar el láser al espesor del material
- Colocar el cabeza sobre el lugar de comienzo del corte
- Probar el area que necesita el corte con el boton FRAME
- Cortar



<h2 id="archivo">Preparación del archivo</h2>

Indicaciónes para cortar en láser

- Usar un programa vectorial
- Cerciorarse que las curvas cerradas están cerradas
- Trabajar el diseño al tamaño real que se va a cortar
- Evitar que dos lineas se superpongan, ya que el láser las cortara dos veces, oscurenciendo el material y creando la posibilidad de fuego
- Convertir todo el textos en curvas


- Exportar el archivo en el formato .DXF
- Al exportar colocar la opción 1 Pulgada = 1 Unidad


<h2 id="seguridad">Seguridad</h2>

IMPORTANTE: El corte láser es una máquina peligrosa, nunca se debe dejar desatendida

<h2 id="normas">Materiales</h2>

IMPORTANTE: No cortar PVC, Vinilo, Materiales con Cloro, o inflamables.
Cualquier material que no se sepa su composición, se asume peligroso y no se corta.



Maderas

| Material | Estrategia | Espesor | Velocidad | Potencia | Potencia Corner | Pasadas | Observacion |
| :---:  |   :---:  | :---:  | :---:  | :---:  | :---:  | :---:  | :---:  |  
|DM|Corte|3 mm|35-55|95|90|1||
|DM|Marcado|3 mm|35-55|95|90|1||
|DM|Marcado|3 mm|90|20|15|1||

Plásticos

| Material | Estrategia | Espesor | Velocidad | Potencia | Potencia Corner | Pasadas | Observacion |
| :---:  |   :---:  | :---:  | :---:  | :---:  | :---:  | :---:  | :---:  |  
|Metacrilato|Corte|3 mm|35|95|90|1||
|Metacrilato|Marcado|3 mm|100|10|6|1||
|Metacrilato|Corte|4 mm|17|20|15|1||
|Metacrilato|Marcado|4 mm|100|20|15|1||
|Metacrilato|Corte|5 mm|17|95|90|1||
|Metacrilato|Marcado|5 mm|100|10|6|1||

Papel - Cartón

Telas

