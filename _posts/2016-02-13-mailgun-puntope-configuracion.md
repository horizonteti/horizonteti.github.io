---
title: "Configuración Mailgun y dominios puntope"
description: "Configuración paso a paso de Mailgun y punto.pe"
layout: post
date: 13/02/2016 18:20
---
Enviar correo desde una aplicación requiere configurar un servidor de correos e incluir librerías especiales en el proyecto. Para evitar esto, nace [mailgun](http://www.mailgun.com/). Mailgun hace disponible un API a los desarrolladores para enviar y recibir correos de manera fácil y sin necesidad de tener un servidor de correos dedicado.

![Mailgun](https://doc-0g-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/v339blufbjskm6qsoru93j6emvfbgsq1/1455400800000/11820878478336017276/*/0B5LOMizfGW_AN3JrcjJsdEQ2dnc?e=view)

# Creación de una cuenta

La creación de una cuenta es sencillo, solo necesita tener una cuenta de correo para verificar su cuenta y completar el siguiente formulario.

![Formulario de registro](https://doc-0k-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/une4v60l2o5vnbt1v347do64soes3k34/1455400800000/11820878478336017276/*/0B5LOMizfGW_Ad2lSYUdUcVZDblE?e=view)

# Configuración del dominio en punto.pe

El dominio se registra en mailgun y para su validación se registra en [punto.pe](http://punto.pe).

![Agregar nuevo dominio](https://doc-0g-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/ljajs6htldcu64a4jpbt32jje57o2npl/1455400800000/11820878478336017276/*/0B5LOMizfGW_AaUxaLWNPbkRGdGc?e=view)

![Ingresar el dominio](https://doc-14-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/9hda018n6ri2fq455k4fh6fphv1org6g/1455400800000/11820878478336017276/*/0B5LOMizfGW_AZXowM0xNdHBYN00?e=view)

Los valores a registrar son TXT y CNAME, como se ven en las imágenes. (ver más.)[https://documentation.mailgun.com/user_manual.html#verifying-your-domain]

(![Ver en Youtube](https://doc-00-3k-docs.googleusercontent.com/docs/securesc/o9meojakf2n92l8h1kms1kaoup4pj1pq/d98jsqrhl4p4370mi5tgou47q196d4a3/1455422400000/11820878478336017276/11252568721233091225/0B5LOMizfGW_AcWN2QkNMRmk5eDQ?e=view&nonce=o33v3lrtncm6m&user=11252568721233091225&hash=bcpcrnaphb6sminedrbc58rsflndmvj2))[https://www.youtube.com/watch?v=ZDK06iRIQkk]

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZDK06iRIQkk" frameborder="0" allowfullscreen></iframe>

![Agregar información del dominio en punto.pe](https://doc-0o-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/igtivrkijdql726gu3npmt2fbl7rtjfh/1455400800000/11820878478336017276/*/0B5LOMizfGW_ASXhnUnAwcGE1dXc?e=view)

![Registro mg.horizonteti.com.pe TXT](https://doc-0g-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/ackrq1kv6muvqgmhbbge7h8l4tgcb4h8/1455400800000/11820878478336017276/*/0B5LOMizfGW_AVjRoa1FkRldjaG8?e=view)

![Registro mg.horizonteti.com.pe TXT 2](https://doc-10-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/f0pgmq8qdppaje0i22a782415pckfk4t/1455400800000/11820878478336017276/*/0B5LOMizfGW_AQzRxcnpVVExhdDA?e=view)

![Registro mg.horizonteti.com.pe CNAME](https://doc-0o-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/90q89p289h8iumitdqtfdpdegkrcucp5/1455400800000/11820878478336017276/*/0B5LOMizfGW_AQktpbkxMUDlReXM?e=view)
