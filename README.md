# Analisis de un cajero

Santiago Gómez Almeyda 20161020503

Jheisson Enrique Fortich Suarez 20172020049

Kevin Andres Malaver Cobos 20171020001

Diagramas de caso de uso realizado con UmlStudio

![alt text](https://github.com/Forson666/Analisis-por-casos-de-uso-de-un-cajero/blob/master/diagrama%20de%20retirar.png)
![alt text](https://github.com/Forson666/Analisis-por-casos-de-uso-de-un-cajero/blob/master/diagrama%20de%20depositar.PNG)
![alt text](https://github.com/Forson666/Analisis-por-casos-de-uso-de-un-cajero/blob/master/diagrama%20de%20transferir.PNG)

O en un solo diagrama:

![Diagrama de casos de uso](https://github.com/Forson666/Analisis-por-casos-de-uso-de-un-cajero/blob/master/diagrama.PNG)

## Diagramas de actividades

![Diagrama de actividades1](https://github.com/Forson666/Diagramas-de-un-cajero/blob/master/diagrama%20de%20actividades%20de%20retiro.png)
![Diagrama de actividades2](https://github.com/Forson666/Diagramas-de-un-cajero/blob/master/diagrama%20de%20actividades%20de%20deposito.png)
![Diagrama de actividades3](https://github.com/Forson666/Diagramas-de-un-cajero/blob/master/diagrama%20de%20actividades%20de%20transferencia.png)

## Diagrama de Clases basado en Diagrama de Casos de Uso

![Diagrama de Clases](https://user-images.githubusercontent.com/20057560/82928070-4c4f9600-9f47-11ea-91a4-197414409601.PNG)

## Diagramas de Secuencia

![SequenceDiagramDepositar](https://user-images.githubusercontent.com/31100374/83358315-4a674780-a338-11ea-9370-14beb8292bfd.png)
![SequenceDiagramRetirar](https://user-images.githubusercontent.com/31100374/83358317-4b987480-a338-11ea-95db-ad06613888dd.png)
![SequenceDiagramTransferir](https://user-images.githubusercontent.com/31100374/83358318-4c310b00-a338-11ea-914c-795eabd41110.png)

## Realizacion de transferencia

![Realizacion](https://github.com/Forson666/Diagramas-de-un-cajero/blob/master/Realizacion%20del%20caso%20de%20transferencia%20en%20el%20modelo%20de%20analisis.png)

## Diagrama de colaboracion de transferencia

![Colaboracion](https://github.com/Forson666/Diagramas-de-un-cajero/blob/master/diagrama%20de%20colaboracion%20para%20la%20transferencia.png)

## Modelo de diseño a partir de modelo de analisis
![WhatsApp Image 2020-06-04 at 8 56 56 AM](https://user-images.githubusercontent.com/31100374/83766128-a20bf880-a641-11ea-99a0-4f7f77b47822.jpeg)

## Diagrama de secuencia para representar caso de uso transferencia
![DiagramaDeDiseño](https://user-images.githubusercontent.com/31100374/83766157-a9330680-a641-11ea-86c9-cc6951d9859a.png)

## Diagrama de implementación apartir del modelo de diseño
![Diseño implementación](https://user-images.githubusercontent.com/20057560/83769805-ea2d1a00-a645-11ea-8739-c0e105f9c6b8.jpeg)

## Prueba de Casos de Uso

Ej. un caso de prueba especifica la entrada, los resultados esperados, y otras
condiciones relevantes para verificar el flujo básico del caso de uso realizar la transfeencia de dinero

### Dinero:

#### Entradas:
La cuenta 14-141-1411 del Cliente de Banco tiene un saldo de 410 $
El Cliente de Banco se identifica correctamente
El Cliente de Banco solicita la transferencia de 200 $ de la cuenta 14-141-1411 hacia la cuenta 27-272-2722
Hay saldo suficiente en la cuenta del cliente

#### Resultados:
El saldo de la cuenta del cliente 14-141-1411 disminuye a 210 $
La cuenta de destino 27-272-2722 recibe 200 $
El Cliente de Banco recibe mensaje de confirmación del Cajero Automático: "Transferencia Realizada".

#### Condiciones:
No se permite que ningún otro caso de uso (instancias de) acceda a la
cuenta 14-141-1411 durante la ejecución del caso de prueba.


