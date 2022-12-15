# Challenge ONE G3 | Java - Sprint 1

## Conversor de moneda

Este primer reto de la ruta Java, ONE - Oracle Next Education, está dirigido a la implementación de un conversor de divisas, utilizando la librería javax.swing, así como a ejecutar los conocimientos adquiridos en los cursos de Alura Latam: primeros pasos; introducción a la orientación a objetos; comprensión de herencia e interfaces; y, comprensión de excepciones.

Con base en lo anterior, se utilizó el modelo venezolano, donde las monedas relevantes son el dólar estadounidense, el euro y algunas criptomonedas con mayor o menor exposición. Asimismo, dicho mercado está influenciado por varios tipos de cambio oficiales e informales, entre los que se encuentran algunos como:

| Oficial | Informal |
| --- | --- |
| Dólar BCV  (sicad2) | DólarToday (dolartoday) |
| Dólar Bitcoin (sicad1) | Cúcuta (efectivo_cucuta) |
| Petro (PTR) (cencoex) | - |

> - BCV: Banco Central de Venezuela;
> - SICAD: Sistema Complementario de Administración de Divisas;
> - PTR: Petro, criptomoneda del estado venezolano;
> - CENCOEX: Centro Nacional de Comercio Exterior.

En cuanto a los tipos de cambio, se importan de la [API DolarToday](https://s3.amazonaws.com/dolartoday/data.json), actualizándose cada 10 minutos. Y, el patrón de diseño es MVC (Modelo-Vista-Controlador) , obteniendo las siguientes clases:

| Diseño | Clase |
| --- | --- |
| Modelo | Tasa.java |
| Vista | Interfaz.java |
| Controlador | Principal.java, ConsumoAPI.java |


funcionalidades;
Cómo pueden usarlo los usuarios;
Donde los usuarios pueden encontrar ayuda sobre su proyecto;
Autores del proyecto.
