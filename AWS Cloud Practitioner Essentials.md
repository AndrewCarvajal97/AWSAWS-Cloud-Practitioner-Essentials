##### Módulo 1: Introducción a Amazon Web Services

- Resumir los beneficios de AWS.
- Describir las diferencias entre la entrega bajo demanda y las implementaciones en la nube.
- Resumir el modelo de precios de pago por uso.

  

##### Módulo 2: Computación en la nube

- Describir los beneficios de Amazon Elastic Compute Cloud (Amazon EC2) a nivel básico.
- Identificar los distintos tipos de instancias de Amazon EC2.
- Diferenciar entre las distintas opciones de facturación de Amazon EC2.
- Describir los beneficios de Amazon EC2 Auto Scaling.
- Resumir los beneficios de Elastic Load Balancing.
- Proporcionar un ejemplo de los usos de Elastic Load Balancing.
- Resumir las diferencias entre Amazon Simple Notification Service (Amazon SNS) y Amazon Simple Queue Services (Amazon SQS).
- Resumir las opciones de computación adicionales de AWS.

  

##### Módulo 3: Infraestructura global y fiabilidad

- Resumir los beneficios de la infraestructura global de AWS.
- Describir el concepto básico de zonas de disponibilidad.
- Describir los beneficios de las ubicaciones perimetrales y Amazon CloudFront.
- Comparar diferentes métodos para aprovisionar servicios de AWS.

  

##### Módulo 4: Redes

- Describir los conceptos básicos de redes.
- Describir la diferencia entre los recursos de redes públicas y privadas.
- Explicar una gateway privada virtual utilizando una situación real.
- Explicar una red privada virtual (VPN) utilizando una situación real.
- Describir los beneficios de AWS Direct Connect.
- Describir los beneficios de las implementaciones híbridas.
- Describir las capas de seguridad utilizadas en una estrategia de TI.
- Describir qué servicios se utilizan para interactuar con la red global de AWS.

  

##### Módulo 5: Almacenamiento y bases de datos

- Resumir el concepto básico de almacenamiento de información y bases de datos.
- Describir los beneficios de Amazon Elastic Block Store (Amazon EBS).
- Describir los beneficios de Amazon Simple Storage Service (Amazon S3).
- Describir los beneficios de Amazon Elastic File System (Amazon EFS).
- Resumir distintas soluciones de almacenamiento.
- Describir los beneficios de Amazon Relational Database Service (Amazon RDS).
- Describir los beneficios de Amazon DynamoDB.
- Resumir distintos servicios de bases de datos.

  

##### Módulo 6: Seguridad

- Explicar los beneficios del modelo de responsabilidad compartida.
- Describir la autenticación multifactor (MFA).
- Diferenciar entre los niveles de seguridad de AWS Identity and Access Management (IAM).
- Describir las políticas de seguridad a nivel básico.
- Explicar los beneficios de AWS Organizations.
- Resumir los beneficios de conformidad de AWS.
- Explicar de los servicios de seguridad principales de AWS a nivel básico.

  

##### Módulo 7: Seguimiento y análisis

- Resumir los enfoques para supervisar el entorno de AWS.
- Describir los beneficios de Amazon CloudWatch.
- Describir los beneficios de AWS CloudTrail.
- Describir los beneficios de AWS Trusted Advisor.

  

##### Módulo 8: Precios y soporte

- Comprender los modelos de soporte y precios de AWS.
- Describir el nivel gratuito de AWS.
- Describir los principales beneficios de AWS Organizations y la facturación unificada.
- Explicar los beneficios de AWS Budgets.
- Explicar los beneficios de AWS Cost Explorer.
- Explicar los principales beneficios de la calculadora de precios de AWS.
- Distinguir entre los distintos planes de AWS Support.
- Describir los beneficios de AWS Marketplace.

  

##### Módulo 9: Migración e innovación

- Comprender la migración y la innovación en la nube de AWS.
- Resumir el AWS Cloud Adoption Framework (AWS CAF).
    
- Resumir seis factores clave de una estrategia de migración a la nube.
    
- Describir los beneficios de varias soluciones de migración de datos de AWS, como AWS Snowcone, AWS Snowball o AWS Snowmobile.
    
- Resumir el amplio alcance de las soluciones innovadoras que ofrece AWS.
    

  

##### Módulo 10: El cambio a la nube

- Resumir los cinco pilares del marco de referencia AWS Well-Architected.
- Explicar los seis beneficios de la informática en la nube.

  

##### Módulo 11: Conceptos básicos de AWS Certified Cloud Practitioner

- Determinar los recursos para la preparación del examen de AWS Certified Cloud Practitioner.
- Describir los beneficios de contar con una certificación de AWS.

![[Pasted image 20231014175148.png]]

# Informática en la nube
La informática en la nube es la entrega bajo demanda de recursos de TI a través de internet con precios de pago por uso.

Se te brindaran los servicios cuando los necesites


Con AWS la idea es soportar el trabajo pesado de IT

---
## Modelos de implementación para informática en la nube

## Basada en la nube

- Lanza toda la aplicación y sus partes en la nube
- Diseña y crea en la nube

En un modelo de **implementación basado en la nube**, puedes migrar aplicaciones existentes a la nube o diseñar y crear nuevas aplicaciones directamente allí. Puedes crearlas en una infraestructura de bajo nivel que requiera que el personal de TI las administre. Otra posibilidad es crearlas utilizando servicios de nivel superior que reduzcan los requisitos de administración, arquitectura y escalado de la infraestructura principal.

Por ejemplo, una empresa podría crear una aplicación compuesta por servidores virtuales, bases de datos y componentes de red que estén completamente basados en la nube.

## Basada en instalaciones

- Implementa recursos mediante herramientas de virtualización y administración de recursos
- Es conocida como la red privada
- 


## Híbrida








Elastic Load Balancing.


Tenencia múltiple: uso compartido del hardware subyacente entre VMs


# Amazon EC2.
https://es.wikipedia.org/wiki/Amazon_EC2

## Tipos de instancia EC2

![[Pasted image 20231015123552.png]]

### Propósito general
tiene un equilibrio de lo que se encargan especificamente las otras instacias

Recursos de apps
computacion
Servicios web
Load balancer
bases de datos medianas

**Las instancias de propósito general** proporcionan un equilibrio entre recursos de computación, memoria y redes. Puedes utilizarlas para diversas cargas de trabajo, tales como:

- Servidores de aplicaciones.
- Servidores de juegos.
- Servidores de backend de aplicaciones para empresas.
- Bases de datos pequeñas y medianas.

Supongamos que tienes una aplicación en la que las necesidades de recursos para la computación, memoria y redes son aproximadamente equivalentes. Puedes decidir iniciarla en una instancia de propósito general porque la aplicación no requiere optimización en ningún área de recursos única.

### de computo optimizada
alta carga de computacion en tareas
computacion de alto rendimiento HPC
Juegos

**Las instancias de computación optimizada** son ideales para aplicaciones vinculadas a la computación que se benefician de procesadores de alto rendimiento. Al igual que las instancias de propósito general, puedes utilizar instancias de computación optimizada para cargas de trabajo como servidores web, aplicaciones o juegos.  
  
Sin embargo, la diferencia es que las aplicaciones de computación optimizada son ideales para servidores web de alto rendimiento, servidores de aplicaciones de uso intensivo de computación y servidores de juegos dedicados. También puedes utilizar este tipo de instancias para cargas de trabajo de procesamiento por lotes que requieran procesar muchas transacciones en un solo grupo.


### instancia de computacion acelerada

**Las instancias de computación acelerada** utilizan aceleradores de hardware o coprocesadores para realizar algunas funciones de la forma más eficiente posible en el software que se inicia en las CPU. Algunos ejemplos de estas funciones incluyen cálculos con números de coma flotante, procesamiento de gráficos y coincidencia de patrones de datos.  
  

En informática, un acelerador de hardware es un componente que puede acelerar el procesamiento de datos. Las instancias de computación acelerada son ideales para cargas de trabajo como aplicaciones gráficas, streaming de juegos y streaming de aplicaciones.

### memoria optimizada
alta carga de memoria
graficos
aceleradores de harware

**Las instancias optimizadas de memoria** están diseñadas para ofrecer un rendimiento rápido para cargas de trabajo que procesan grandes conjuntos de datos en la memoria. En computación, la memoria es un área de almacenamiento temporal. Contiene todos los datos e instrucciones que necesita una unidad central de procesamiento (CPU) para poder completar acciones. Para poder iniciar un programa o una aplicación de ordenador, debe cargarse desde el almacenamiento a la memoria. Este proceso de precarga proporciona a la CPU acceso directo al programa informático.


Supongamos que tienes una carga de trabajo que requiere que se carguen previamente grandes cantidades de datos antes de iniciar una aplicación. En este escenario, puede tratarse de una base de datos de alto rendimiento o de una carga de trabajo que implique procesar en tiempo real una gran cantidad de datos no estructurados. En este tipo de casos prácticos, considera la posibilidad de utilizar una instancia optimizada de memoria. Estas permiten llevar a cabo cargas de trabajo con altas necesidades de memoria y obtener un excelente rendimiento.
### optimizadas para almacenamiento
alta carga de datos locales

**Las instancias optimizadas para el almacenamiento** están diseñadas para cargas de trabajo que requieren acceso de lectura y escritura alto y secuencial a grandes conjuntos de datos en el almacenamiento local. Algunos ejemplos de cargas de trabajo adecuadas para este tipo de instancias incluyen sistemas de archivos distribuidos, aplicaciones de data warehousing y sistemas de procesamiento de transacciones en línea de alta frecuencia (OLTP).  
  

En informática, el término operaciones de entrada/salida por segundo (IOPS) es una métrica que mide el rendimiento de un dispositivo de almacenamiento. Indica cuántas operaciones de entrada o salida diferentes puede realizar un dispositivo en un segundo. Las instancias optimizadas para el almacenamiento están diseñadas para ofrecer decenas de miles de IOPS aleatorias y de baja latencia a las aplicaciones. 

  

Puede pensar en las operaciones de entrada como datos introducidos en un sistema, como los registros introducidos en una base de datos. Una operación de salida son datos generados por un servidor. Un ejemplo de salida podría ser el análisis realizado en los registros de una base de datos. Si tiene una aplicación que tiene un alto requisito de IOPS, una instancia optimizada para el almacenamiento puede proporcionar un mejor rendimiento en comparación con otros tipos de instancias no optimizadas para este tipo de caso práctico.




## Precios de EC2


### bajo demanda
suelen ser costos por tiempo de uso computacional (sale mas caro y se usa regularmente para testeo de apps y desarrollo mas no produccion)

Las **instancias bajo demanda** son ideales para cargas de trabajo irregulares a corto plazo que no se pueden interrumpir. No se aplican costes iniciales ni contratos mínimos. Las instancias se inician continuamente hasta que las detienes y solo pagas por el tiempo de computación que usas.  
  
Algunos ejemplos de casos prácticos para instancias bajo demanda incluyen el desarrollo y la prueba de aplicaciones, y el arranque de aplicaciones que tienen patrones de uso impredecibles. Las instancias bajo demanda no se recomiendan para cargas de trabajo que duran un año o más porque estas cargas de trabajo pueden experimentar un mayor ahorro de costes mediante instancias reservadas.

### planes de ahorro

AWS ofrece planes de ahorro para varios servicios de computación, incluido Amazon EC2. **Los planes de ahorro de Amazon EC2** te permiten reducir los costes de computación si te comprometes a un uso de computación constante durante un periodo de 1 o 3 años. El compromiso durante este periodo se traduce en un ahorro de hasta un 72 % en comparación con los costes bajo demanda.  
  

Cualquier uso que no supere el compromiso se cobra según la tarifa del plan de ahorro con descuento (por ejemplo, 10 USD la hora). El uso que supere el compromiso se cobra según las tarifas bajo demanda habituales.  
  

Más adelante en el curso, verás AWS Cost Explorer, una herramienta que te permitirá visualizar, comprender y administrar los costes y el uso de AWS a lo largo del tiempo. Si estás barajando opciones de planes de ahorro, AWS Cost Explorer puede analizar tu uso de Amazon EC2 durante los últimos 7, 30 o 60 días. AWS Cost Explorer también ofrece recomendaciones personalizadas para planes de ahorro. Estas recomendaciones realizan una estimación de cuánto podrías ahorrar en los costes mensuales de Amazon EC2, según el uso previo de Amazon EC2 y el importe del compromiso por hora en un plan de ahorro de 1 o 3 años.

### instancias reservadas
Las **instancias reservadas** son un descuento de facturación que se aplica al uso de instancias bajo demanda en tu cuenta. Puedes comprar instancias reservadas estándar y convertibles para un periodo de 1 o 3 años, e instancias reservadas programadas para un periodo de 1 año. Lograrás un mayor ahorro de costes con la opción de 3 años.


Al final de un periodo de instancia reservada, puedes seguir utilizando la instancia de Amazon EC2 sin interrupción. Sin embargo, se te cobrarán tarifas bajo demanda hasta que realices una de las siguientes acciones:

- Terminar la instancia.
- Adquirir una nueva instancia reservada que coincida con los atributos de instancia (tipo de instancia, región, tenencia y plataforma).




### instancias spot

(tiene definido el ciclo de inicio-fin)

- la spot  utiliza las instancias no usadas de ec2 lo que dificulta su disponibilidad y estan sjetas a interrupiones

Las **instancias de spot** son ideales para cargas de trabajo con horarios de inicio y fin flexibles, o que pueden soportar interrupciones. Estas instancias utilizan la capacidad de computación de Amazon EC2 no utilizada y ofrecen ahorro de costes con hasta un 90 % de descuento en los precios bajo demanda.  
  
Supongamos que tienes un trabajo de procesamiento en segundo plano que puede iniciarse y detenerse según sea necesario (como el trabajo de procesamiento de datos de una encuesta de clientes). Lo deseable es iniciar y detener el trabajo de procesamiento sin que afecte a las operaciones generales de la empresa. Si realizas una petición de spot y la capacidad de Amazon EC2 está disponible, se lanzará la instancia de spot. Sin embargo, si realizas una petición de spot y la capacidad de Amazon EC2 no está disponible, la petición no se realizará correctamente hasta que la capacidad esté disponible. La capacidad no disponible puede retrasar el lanzamiento del trabajo de procesamiento en segundo plano.  
  
Después de lanzar una instancia de spot, si la capacidad ya no está disponible o aumenta la demanda de dichas instancias, es posible que la instancia se interrumpa. Puede que esto no suponga ningún problema para el trabajo de procesamiento en segundo plano. Sin embargo, en el ejemplo anterior de desarrollo y prueba de aplicaciones, lo más probable es que desees evitar interrupciones inesperadas. Por lo tanto, elige otro tipo de instancia EC2 más adecuado para esas tareas.


### hosts dedicados

**Los hosts dedicados** son servidores físicos con capacidad de instancias de Amazon EC2 totalmente dedicada a su uso. 

Puedes utilizar las licencias de software existentes por socket, por núcleo o por VM para ayudar a mantener la conformidad de las licencias. Puedes comprar reservas de hosts dedicados y hosts dedicados bajo demanda. De todas las opciones de Amazon EC2 cubiertas, los hosts dedicados son los más caros.


# Amazon EC2 Auto Scaling
## Capacidad y elasticidad 

![[Pasted image 20231015132523.png]]

<aside></aside>
<aside>Amazon EC2 Auto Scaling te permite agregar o eliminar automáticamente instancias de Amazon EC2 en respuesta a la demanda cambiante de las aplicaciones. Al escalar automáticamente las instancias horizontal y verticalmente según sea necesario, puedes mantener una mayor sensación de disponibilidad de las aplicaciones.

En Amazon EC2 Auto Scaling, puedes utilizar dos estrategias: escalado dinámico y escalado predictivo.

- _El escalado dinámico_ responde a la demanda cambiante. 
- El _escalado predictivo_ programa automáticamente el número correcto de instancias de Amazon EC2 en función de la demanda prevista.</s>

## escalado vertical y horizontal

crea instancias y detiene las instancias segun sea la demanda y capacidad no usada


### vertical 

- agregar potencia de maquinas en uso
- aprovisionar el exceso
- dedica la potencia para el proceso que come mas recurso
- 





![[Pasted image 20231015135746.png]]

> [!WARNIGN]
> Si no especificas el número deseado de instancias de Amazon EC2 en un grupo de Auto Scaling, la capacidad deseada se establece de forma predeterminada en su capacidad mínima.


Es importante establecer las instancias maximas a usar cuando haya demanda

# Dirección de tráfico con Elastic Load Balancing

definir que las instancias tengan funciones diferentes
- LB es un intermediario para distribuir correctamente el trafico
- es regional, lo que significa es cuenta con alta disponibilidad para la infraestructura global, ya que no se aplica individualmente a instancias

![[Pasted image 20231015151157.png]]



# Mensajeria y colas


buffer



La comunicación entre aplicaciones directamente se llama acoplamiento ajustado.


La mensajería puede ser síncrona (donde las partes esperan una respuesta inmediata) o asíncrona (donde las partes pueden continuar trabajando sin esperar una respuesta inmediata).
## arquitectura monolitica

![[Pasted image 20231015154818.png]]

Las aplicaciones están formadas de varios componentes. Los componentes se comunican entre sí para transmitir datos, satisfacer solicitudes y mantener la aplicación en uso. 

Supongamos que tienes una aplicación con componentes estrechamente acoplados. Estos componentes pueden incluir bases de datos, servidores, interfaz de usuario, lógica empresarial, etc. Este tipo de arquitectura puede considerarse una **aplicación monolítica**. 

En esta estrategia de arquitectura de aplicaciones, si falla un componente, otros componentes fallan y, probablemente, toda la aplicación fallará.
## microservicios

![[Pasted image 20231015154828.png]]

En una estrategia de microservicios, los componentes de la aplicación están acoplados débilmente. En este caso, si falla un solo componente, los demás componentes siguen funcionando porque están comunicados entre sí. El acoplamiento débil evita que toda la aplicación falle. 

Cuando diseñes aplicaciones en AWS, puedes adoptar la estrategia de microservicios con servicios y componentes que cumplan diferentes funciones. Dos servicios facilitan la integración de aplicaciones: Amazon Simple Notification Service (Amazon SNS) y Amazon Simple Queue Service (Amazon SQS).

## **Amazon Simple Queue Service (Amazon SQS)** 

es un servicio de cola de mensajes entre los componentes de software 

Con Amazon SQS, puedes enviar, almacenar y recibir mensajes entre componentes de software, sin perder mensajes y sin necesidad de que otros servicios estén disponibles. En Amazon SQS, una aplicación envía mensajes a una cola. Un usuario o un servicio extrae un mensaje de la cola, lo procesa y, a continuación, lo elimina de la cola.




# Sin servidor 

El término "sin servidor" significa que el código se inicia en servidores, pero no es necesario aprovisionar ni administrar dichos servidores. Con la computación sin servidor, puedes centrarte más en innovar con productos y características nuevas, y no en el mantenimiento de los servidores.

Otro beneficio es la flexibilidad de escalar aplicaciones sin servidor automáticamente. La computación sin servidor puede ajustar la capacidad de las aplicaciones modificando las unidades de consumo, como el rendimiento y la memoria. 

Un servicio de AWS para la computación sin servidor es **AWS Lambda**.

## AWS Lambda
desecadenador = trigger (es un evento que inicia la ejecución de una función Lambda.)
![[Pasted image 20231015164513.png]]
[**AWS Lambda**](https://aws.amazon.com/lambda) es un servicio que permite iniciar código sin necesidad de aprovisionar ni administrar servidores. 

Cuando se utiliza AWS Lambda, solo se paga por el tiempo de computación que se consume. Los cargos solo se aplican cuando el código está en funcionamiento. También se puede iniciar código para prácticamente cualquier tipo de aplicación o servicio backend, todo sin necesidad de administración. 

Por ejemplo, una función Lambda sencilla podría implicar cambiar automáticamente el tamaño de las imágenes cargadas en la nube de AWS. En este caso, la función se activa cuando se carga una nueva imagen.


# Amazon Elastic Container Service (Amazon ECS)



# Amazon Elastic Kubernetes Service (Amazon _EKS_)


















---
# ChatGPT Wiki









## Networking

Para trabajar con servicios de Amazon Web Services (AWS) de manera básica en el ámbito de redes, es importante tener conocimientos fundamentales sobre redes y conceptos relacionados. Aquí te proporciono una lista de conceptos clave que debes conocer:

1. **VPC (Virtual Private Cloud)**: AWS permite crear una red virtual aislada para tus recursos, conocida como VPC. Debes comprender cómo crear y configurar una VPC y cómo se relaciona con otros servicios.

2. **Subredes (Subnets)**: Las subredes son divisiones lógicas de una VPC que te permiten organizar tus recursos y aplicaciones. Es importante entender cómo se crean y configuran las subredes, y cómo se asocian a una VPC.

3. **Grupos de seguridad (Security Groups)**: Los grupos de seguridad son cortafuegos virtuales que controlan el tráfico de entrada y salida de las instancias EC2. Debes saber cómo crear y configurar reglas de seguridad.

4. **Route Tables (Tablas de ruteo)**: Las tablas de ruteo determinan cómo se dirige el tráfico dentro de tu VPC y hacia fuera de ella. Debes comprender cómo se configuran las tablas de ruteo.

5. **Direcciones IP Elásticas**: Las direcciones IP elásticas son direcciones IP estáticas que puedes asignar a instancias EC2. Es importante saber cómo asignar y liberar direcciones IP elásticas.

6. **Balanceadores de carga (Load Balancers)**: Los balanceadores de carga distribuyen el tráfico entre varias instancias para mejorar la disponibilidad y la escalabilidad. Debes entender cómo configurarlos y cómo funcionan.

7. **AWS Direct Connect**: Es un servicio que permite establecer una conexión de red dedicada entre tu infraestructura local y AWS. Debes conocer cómo configurar y usar AWS Direct Connect.

8. **VPN (Virtual Private Network)**: AWS admite conexiones VPN para conectar tu red local con tu VPC. Debes entender cómo configurar una VPN y cómo asegurar la comunicación.

9. **Amazon Route 53**: Es el servicio de DNS de AWS. Debes saber cómo crear y administrar zonas DNS, registros y configuraciones de enrutamiento.

10. **NAT Gateway**: Un NAT Gateway permite que las instancias en una subred privada accedan a Internet. Debes comprender su función y cómo configurarlo.

11. **Peering de VPC**: AWS permite conectar VPCs entre sí a través de peering. Debes entender cómo configurar y gestionar conexiones de peering.

12. **Amazon CloudFront**: Es el servicio de CDN (Content Delivery Network) de AWS. Debes conocer cómo usarlo para distribuir contenido de manera eficiente.

Estos son conceptos básicos que te ayudarán a comprender y configurar la infraestructura de red en AWS. A medida que profundices en el uso de AWS, podrás explorar temas más avanzados según tus necesidades específicas.


## EC2
Amazon Elastic Compute Cloud (Amazon EC2) ofrece una amplia variedad de instancias de máquinas virtuales que están diseñadas para satisfacer diferentes necesidades de cómputo, desde aplicaciones simples hasta cargas de trabajo altamente exigentes. Cada instancia de EC2 tiene diferentes características en términos de capacidad de procesamiento, memoria, almacenamiento y opciones de red. A continuación, te proporciono una descripción general de las familias de instancias más comunes en AWS:

1. **Familia T (Burstable Performance)**: Estas instancias son ideales para cargas de trabajo intermitentes o de bajo tráfico. Tienen la capacidad de "t2.micro", "t3.small", "t4g.large", etc. Pueden gastar créditos de rendimiento durante los picos y recargarlos durante los periodos de inactividad.

2. **Familia M (Balanceadas)**: Ofrecen un equilibrio entre CPU, memoria y almacenamiento. Ejemplos incluyen "m5.large", "m4.xlarge", etc. Son adecuadas para aplicaciones web, bases de datos y aplicaciones empresariales.

3. **Familia C (Optimizadas para CPU)**: Estas instancias proporcionan un alto rendimiento de CPU, pero pueden tener menos memoria que otras familias. Ejemplos incluyen "c5.xlarge", "c4.2xlarge", etc. Son ideales para cargas de trabajo intensivas en CPU como análisis de datos y cómputo científico.

4. **Familia R (Memoria optimizada)**: Estas instancias están diseñadas para aplicaciones que requieren una gran cantidad de memoria. Ejemplos incluyen "r5.large", "r4.4xlarge", etc. Son ideales para bases de datos en memoria y análisis de datos en memoria.

5. **Familia I (Almacenamiento optimizado)**: Ofrecen un alto rendimiento de almacenamiento, lo que las hace adecuadas para aplicaciones que requieren E/S intensiva. Ejemplos incluyen "i3.large", "i3.2xlarge", etc. Son ideales para bases de datos NoSQL y aplicaciones de análisis de alto rendimiento.

6. **Familia G (GPU)**: Estas instancias están equipadas con unidades de procesamiento gráfico (GPU) y son ideales para cargas de trabajo que requieren aceleración de GPU, como aprendizaje profundo, visualización 3D y procesamiento de gráficos.

7. **Familia P (Procesamiento paralelo)**: Estas instancias están diseñadas para cargas de trabajo de alto rendimiento y procesamiento paralelo, como análisis de alto rendimiento y aplicaciones científicas.

8. **Familia X (Memoria y almacenamiento extremos)**: Ofrecen una gran cantidad de memoria y almacenamiento. Ejemplos incluyen "x1.large", "x1e.32xlarge", etc. Son ideales para bases de datos en memoria de gran escala y análisis de datos.

9. **Familia A (Económicas, basadas en Arm)**: Estas instancias utilizan procesadores ARM y son ideales para cargas de trabajo de bajo costo y eficiencia energética.

10. **Familia D (Uso general con almacenamiento SSD)**: Ofrecen un equilibrio entre CPU, memoria y almacenamiento SSD de alto rendimiento.

Estas son algunas de las familias de instancias más comunes en AWS. La elección de la instancia dependerá de las necesidades específicas de tu aplicación, como el rendimiento, la memoria, el almacenamiento y el presupuesto. Puedes utilizar la calculadora de precios de AWS para estimar el costo de diferentes tipos de instancias y seleccionar la más adecuada para tu caso de uso.


