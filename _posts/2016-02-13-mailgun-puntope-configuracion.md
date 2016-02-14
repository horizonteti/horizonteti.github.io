---
title: "Configuración Mailgun y dominios punto.pe"
description: "Configuración paso a paso de Mailgun y punto.pe"
layout: post
date: 13/02/2016 18:20
---
Enviar correo desde una aplicación requiere configurar un servidor de correos e incluir librerías especiales en el proyecto. Para evitar esto, nace [mailgun](http://www.mailgun.com/). Mailgun hace disponible un API a los desarrolladores para enviar y recibir correos de manera fácil y sin necesidad de tener un servidor de correos dedicado.

![Mailgun](https://doc-0g-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/v339blufbjskm6qsoru93j6emvfbgsq1/1455400800000/11820878478336017276/*/0B5LOMizfGW_AN3JrcjJsdEQ2dnc?e=view)

# Creación de una cuenta

Para crear una nueva cuenta sólo debe registrarse en la siguiente dirección: (http://www.mailgun.com/)[http://www.mailgun.com/].

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZDK06iRIQkk" frameborder="0" allowfullscreen></iframe>

# Configuración del dominio en punto.pe

El dominio se registra en (mailgun)[http://www.mailgun.com/] y su validación se hace mediante el registro de records en el proveedor de dominios [punto.pe](http://punto.pe).

<iframe width="560" height="315" src="https://www.youtube.com/embed/YQe-Ab_Voto" frameborder="0" allowfullscreen></iframe>

<div class="row">
  <div class="col-sm-4 col-sm-offset-4">
    <div class="thumbnail">
      ![Agregar nuevo dominio](https://doc-0g-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/ljajs6htldcu64a4jpbt32jje57o2npl/1455400800000/11820878478336017276/*/0B5LOMizfGW_AaUxaLWNPbkRGdGc?e=view)
      <div class="caption">
        <h3>Agregar nuevo dominio en mailgun</h3>
      </div>
    </div>
  </div>
</div>

![Ingresar el dominio](https://doc-14-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/9hda018n6ri2fq455k4fh6fphv1org6g/1455400800000/11820878478336017276/*/0B5LOMizfGW_AZXowM0xNdHBYN00?e=view)

Los valores a registrar son TXT y CNAME, como se ven en las imágenes. (ver más.)[https://documentation.mailgun.com/user_manual.html#verifying-your-domain]

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZDK06iRIQkk" frameborder="0" allowfullscreen></iframe>

![Agregar información del dominio en punto.pe](https://doc-0o-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/igtivrkijdql726gu3npmt2fbl7rtjfh/1455400800000/11820878478336017276/*/0B5LOMizfGW_ASXhnUnAwcGE1dXc?e=view)

![Registro mg.horizonteti.com.pe TXT](https://doc-0g-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/ackrq1kv6muvqgmhbbge7h8l4tgcb4h8/1455400800000/11820878478336017276/*/0B5LOMizfGW_AVjRoa1FkRldjaG8?e=view)

![Registro mg.horizonteti.com.pe TXT 2](https://doc-10-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/f0pgmq8qdppaje0i22a782415pckfk4t/1455400800000/11820878478336017276/*/0B5LOMizfGW_AQzRxcnpVVExhdDA?e=view)

![Registro mg.horizonteti.com.pe CNAME](https://doc-0o-34-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/90q89p289h8iumitdqtfdpdegkrcucp5/1455400800000/11820878478336017276/*/0B5LOMizfGW_AQktpbkxMUDlReXM?e=view)
