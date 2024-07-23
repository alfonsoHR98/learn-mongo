# Operadores de Comparación:

## $eq

Coincide con valores que son iguales a un valor especificado.

## $gt

Coincide con valores que son mayores que un valor especificado.

## $gte

Coincide con valores que son mayores o iguales a un valor especificado.

## $in

Coincide con cualquiera de los valores especificados en un arreglo.

## $lt

Coincide con valores que son menores que un valor especificado.

## $lte

Coincide con valores que son menores o iguales a un valor especificado.

## $ne

Coincide con todos los valores que no son iguales a un valor especificado.

## $nin

Coincide con ninguno de los valores especificados en un arreglo.

# Operadores Lógicos:

## $and

Combina cláusulas de consulta con un AND lógico y devuelve documentos que cumplen ambas condiciones.

## $not

Invierte el efecto de una expresión de consulta y devuelve documentos que no cumplen la expresión de consulta.

## $nor

Combina cláusulas de consulta con un NOR lógico y devuelve documentos que no cumplen ambas condiciones.

## $or

Combina cláusulas de consulta con un OR lógico y devuelve documentos que cumplen cualquiera de las condiciones.

# Operadores de Elementos:

## $exists

Coincide con documentos que tienen el campo especificado.

## $type

Selecciona documentos si un campo es del tipo especificado.

# Operadores de Evaluación:

## $expr

Permite el uso de expresiones de agregación dentro del lenguaje de consulta.

## $jsonSchema

Valida documentos frente a un esquema JSON dado.

## $mod

Realiza una operación de módulo en el valor de un campo y selecciona documentos con un resultado especificado.

## $regex

Selecciona documentos donde los valores coinciden con una expresión regular especificada.

## $text

Realiza una búsqueda de texto.

## $where

Coincide con documentos que satisfacen una expresión JavaScript.

# Operadores Geoespaciales:

## $geoIntersects

Selecciona geometrías que intersectan con una geometría GeoJSON.

## $geoWithin

Selecciona geometrías dentro de una geometría GeoJSON delimitante.

## $near

Devuelve objetos geoespaciales en proximidad a un punto (requiere un índice geoespacial).

## $nearSphere

Devuelve objetos geoespaciales en proximidad a un punto en una esfera (requiere un índice geoespacial).

# Operadores de Arreglos:

## $all

Coincide con arreglos que contienen todos los elementos especificados en la consulta.

## $elemMatch

Selecciona documentos si un elemento en el campo de arreglo cumple con todas las condiciones especificadas.
