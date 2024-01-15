## Servicios principales de AWS

AWS ofrece decenas de servicios en la nube, aquí se reseñan los principales, incluyendo los referentes a la `seguridad`.

La `capa gratuita` es cambiante, algunos enlaces pueden estar rotos o desactualizados.

### Generales

1. **AWS S3 (Amazon Simple Storage Service):**
   - *Descripción:* Almacenamiento de objetos escalable y duradero.
   - *Capa Gratuita:* Hasta 5 GB de almacenamiento estándar por mes durante 12 meses.
   - [Documentación de Amazon S3](https://docs.aws.amazon.com/s3/index.html)

2. **Amazon EC2 (Elastic Compute Cloud):**
   - *Descripción:* Máquinas virtuales escalables en la nube.
   - *Capa Gratuita:* Ofrece 750 horas de instancia t2.micro cada mes durante 12 meses.
   - [Documentación de Amazon EC2](https://docs.aws.amazon.com/ec2/index.html)

3. **AWS Lambda:**
   - *Descripción:* Computación sin servidor para ejecutar código sin aprovisionar servidores.
   - *Capa Gratuita:* Incluye 1 millón de solicitudes gratuitas y 400,000 GB-seconds de tiempo de ejecución por mes.
   - [Documentación de AWS Lambda](https://docs.aws.amazon.com/lambda/index.html)

4. **Amazon RDS (Relational Database Service):**
   - *Descripción:* Servicio de base de datos relacional completamente administrado.
   - *Capa Gratuita:* Hasta 750 horas de instancia db.t2.micro cada mes durante 12 meses.
   - [Documentación de Amazon RDS](https://docs.aws.amazon.com/rds/index.html)

5. **Amazon VPC (Virtual Private Cloud):**
   - *Descripción:* Redes virtuales aisladas en la nube.
   - *Capa Gratuita:* Incluye 5 VPCs, 50 subnets y 1 Elastic IP por mes.
   - [Documentación de Amazon VPC](https://docs.aws.amazon.com/vpc/index.html)

6. **Amazon SNS (Simple Notification Service):**
   - *Descripción:* Servicio de mensajería para la entrega de notificaciones.
   - *Capa Gratuita:* Ofrece 1 millón de notificaciones push y 1 millón de suscripciones al mes.
   - [Documentación de Amazon SNS](https://docs.aws.amazon.com/sns/index.html)

7. **Amazon SQS (Simple Queue Service):**
   - *Descripción:* Servicio de cola de mensajes completamente administrado.
   - *Capa Gratuita:* Incluye 1 millón de solicitudes de mensajes y 1 GB de almacenamiento de mensajes al mes.
   - [Documentación de Amazon SQS](https://docs.aws.amazon.com/sqs/index.html)

8. **AWS Glue:**
   - *Descripción:* Servicio de preparación y carga de datos para análisis.
   - *Capa Gratuita:* Ofrece 1 DPU (Data Processing Unit) y 2 unidades de trabajo de desarrollo por mes.
   - [Documentación de AWS Glue](https://docs.aws.amazon.com/glue/index.html)

9. **Amazon DynamoDB:**
   - *Descripción:* Base de datos NoSQL completamente administrada.
   - *Capa Gratuita:* Incluye 25 GB de almacenamiento y suficiente capacidad de lectura y escritura para 200 millones de solicitudes al mes.
   - [Documentación de Amazon DynamoDB](https://docs.aws.amazon.com/dynamodb/index.html)

### Seguridad

1. **AWS IAM (Identity and Access Management):**

   - *Descripción:* Gestión de identidades y accesos en AWS.
   - *Capa Gratuita:* Incluye el uso gratuito de AWS Identity and Access Management (IAM).
   - [Documentación de AWS IAM](https://docs.aws.amazon.com/iam/index.html)

2. **Amazon GuardDuty:**

   - *Descripción:* Servicio de detección de amenazas gestionado.
   - *Capa Gratuita:* Evaluación gratuita disponible, consulta la [página de precios](https://aws.amazon.com/guardduty/pricing/) de GuardDuty para detalles.

3. **AWS WAF (Web Application Firewall):**

   - *Descripción:* Firewall de aplicaciones web que ayuda a proteger las aplicaciones web de ataques.
   - *Capa Gratuita:* Consulta la [página de precios](https://aws.amazon.com/waf/pricing/) de AWS WAF para detalles sobre la capa gratuita.

4. **AWS KMS (Key Management Service):**

   - *Descripción:* Servicio de administración de claves para el cifrado de datos.
   - *Capa Gratuita:* Consulta la [página de precios](https://aws.amazon.com/kms/pricing/) de AWS KMS para detalles sobre la capa gratuita.

5. **AWS Secrets Manager:**

   - *Descripción:* Almacenamiento y recuperación seguros de información de configuración sensible.
   - *Capa Gratuita:* Consulta la [página de precios](https://aws.amazon.com/secretsmanager/pricing/) de AWS Secrets Manager para detalles sobre la capa gratuita.

6. **AWS Certificate Manager:**

   - *Descripción:* Gestión de certificados SSL/TLS para implementaciones en AWS.
   - *Capa Gratuita:* Consulta la [página de precios](https://aws.amazon.com/certificate-manager/pricing/) de AWS Certificate Manager para detalles sobre la capa gratuita.

7. **Amazon Macie:**

   - *Descripción:* Servicio de seguridad que utiliza el aprendizaje automático para proteger datos confidenciales.
   - *Capa Gratuita:* Evaluación gratuita disponible, consulta la [página de precios](https://aws.amazon.com/macie/pricing/) de Macie para detalles.

8. **AWS CloudHSM (Hardware Security Module):**

   - *Descripción:* Módulo de seguridad de hardware dedicado para la protección de claves criptográficas.
   - *Capa Gratuita:* No hay una capa gratuita para AWS CloudHSM, se factura según el uso. Consulta la [página de precios](https://aws.amazon.com/cloudhsm/pricing/) para detalles.

9. **AWS Firewall Manager:**

   - *Descripción:* Servicio de administración centralizada de políticas de firewall.
   - *Capa Gratuita:* Evaluación gratuita disponible, consulta la [página de precios](https://aws.amazon.com/firewall-manager/pricing/) de AWS Firewall Manager para detalles.

10. **Amazon Inspector:**

      - *Descripción:* Evaluación automática de aplicaciones en busca de vulnerabilidades de seguridad.
      - *Capa Gratuita:* Consulta la [página de precios](https://aws.amazon.com/inspector/pricing/) de Amazon Inspector para detalles sobre la capa gratuita.

11. **AWS Managed Microsoft AD (AWS Directory Service):**

      - *Descripción:* Servicio de directorio administrado para cargas de trabajo de Microsoft.
      - *Capa Gratuita:* No hay una capa gratuita para este servicio. Se factura según el uso. Consulta la [página de precios](https://aws.amazon.com/directoryservice/pricing/) para detalles.

12. **Amazon VPC Traffic Mirroring:**

      - *Descripción:* Copia de tráfico de red para análisis y detección de amenazas.
      - *Capa Gratuita:* Consulta la [página de precios](https://aws.amazon.com/vpc/pricing/) de Amazon VPC para detalles sobre la capa gratuita.

13. **AWS CloudTrail:**

      - *Descripción:* Servicio de registro que realiza un seguimiento de las acciones realizadas en AWS.
      - *Capa Gratuita:* Consulta la [página de precios](https://aws.amazon.com/cloudtrail/pricing/) de AWS CloudTrail para detalles sobre la capa gratuita.

14. **Amazon Detective:**

      - *Descripción:* Servicio de análisis de comportamiento para investigar actividades sospechosas.
      - *Capa Gratuita:* No hay una capa gratuita para Amazon Detective. Se factura según el uso. Consulta la [página de precios](https://aws.amazon.com/detective/pricing/) para detalles.

15. **AWS Security Hub:**

      - *Descripción:* Servicio centralizado para administrar alertas de seguridad y controles de cumplimiento.
      - *Capa Gratuita:* Evaluación gratuita disponible, consulta la [página de precios](https://aws.amazon.com/security-hub/pricing/) de AWS Security Hub para detalles.

---

## De interés

Una referencia general a la nomenclatura en `AWS` aquí:

> <https://docs.aws.amazon.com/es_es/glossary/latest/reference/glos-chap.html>

`AWS`También ofrece diferentes itinerarios de formación para aprender, y eventualmente certificarse, en sus tecnologías:

> <https://www.aws.training/>

> <https://aws.amazon.com/training/>

> [Skillbuilder](https://explore.skillbuilder.aws/learn)

> [Docs](https://docs.aws.amazon.com/index.html)
---
