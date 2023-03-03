![image](https://user-images.githubusercontent.com/125692246/222421187-2b672e4b-cc62-468c-a619-d9f2e57f8fdc.png)


![Gestión Ciber](https://user-images.githubusercontent.com/125692246/222458612-d5944c9e-527c-436d-a85c-14b671d49f4e.jpg)

______________________________________________________________________

![image](https://user-images.githubusercontent.com/125692246/222421225-fd34f6f3-708b-40c6-8419-2a4b882c4bae.png)

La Gestión de Identidad y Acceso (IAM, por sus siglas en inglés) es un marco de políticas y tecnologías utilizadas para gestionar identidades digitales y derechos de acceso a recursos. El aprovisionamiento y el desaprovisionamiento son dos componentes clave de IAM.

[APROVISIONAMIENTO](https://learn.microsoft.com/es-es/microsoft-identity-manager/mim-how-provision-users-adds "Aprovisionamiento").: El aprovisionamiento es el proceso de otorgar acceso a recursos, como aplicaciones, datos y sistemas, a un individuo o grupo. Este proceso incluye la creación de cuentas de usuario, la asignación de roles y permisos, y la configuración de políticas de acceso. El aprovisionamiento puede realizarse de manera manual o mediante herramientas y flujos de trabajo automatizados.

![image](https://user-images.githubusercontent.com/125692315/222619463-8a020fc6-e25d-42f7-906b-6c55f2e60302.png)


[DESAPROVISIONAMIENTO](https://learn.microsoft.com/es-es/azure/iot-dps/how-to-unprovision-devices) El desaprovisionamiento, es el proceso de revocar el acceso a los recursos cuando ya no es necesario. Esto podría deberse a que un empleado deja la empresa o a un cambio en las responsabilidades laborales. El desaprovisionamiento implica desactivar las cuentas de usuario, revocar privilegios y permisos, y asegurarse de que el usuario ya no tenga acceso a ningún dato confidencial o sensible.

![image](https://user-images.githubusercontent.com/125692315/222619926-ed98a57f-c83a-4a82-898b-1c1107753967.png)

Las prácticas efectivas de aprovisonamiento y desaprovisionamiento son esenciales para mantener la seguridad e integridad de los activos digitales de una organización. Un sistema IAM bien diseñado puede ayudar a las organizaciones a garantizar que el acceso a los recursos se otorgue solo al personal autorizado y que se revoque cuando ya no sea necesario. Esto puede ayudar a prevenir brechas de seguridad, pérdida de datos y otros riesgos cibernéticos.


______________________________________________________________________

![image](https://user-images.githubusercontent.com/125692246/222421263-c7ad469f-f88f-447a-9eca-7666e08b6958.png)

[Inicio de sesión único (SSO)](https://www.ibm.com/co-es/topics/single-sign-on#:~:text=El%20inicio%20de%20sesi%C3%B3n%20%C3%BAnico%20(SSO)%20es%20un%20esquema%20de,esa%20sesi%C3%B3n%20sin%20necesidad%20de) es una tecnología de autenticación que permite a los usuarios acceder a múltiples aplicaciones y sistemas de software con una sola identidad y conjunto de credenciales de inicio de sesión. En lugar de tener que ingresar credenciales separadas para cada aplicación, el usuario solo necesita iniciar sesión una vez, lo que le permite acceder a todas las aplicaciones y sistemas de software que estén configurados para SSO.

La tecnología SSO es posible gracias a la utilización de una infraestructura de autenticación centralizada, que almacena y gestiona las credenciales de usuario. Los usuarios pueden autenticarse en esta infraestructura una vez mediante el uso de una contraseña, una tarjeta inteligente, una autenticación biométrica u otros métodos de autenticación, y luego acceder a las aplicaciones y sistemas de software que estén configurados para SSO sin necesidad de volver a autenticarse.

El SSO ofrece varios beneficios, como una experiencia de usuario más fácil y sin interrupciones, reducción de la carga de trabajo del personal de soporte técnico, mayor seguridad, y reducción de los costos de licencias de software y gestión de contraseñas. Sin embargo, también puede presentar riesgos de seguridad si no se implementa adecuadamente, como el riesgo de que un atacante obtenga acceso a varias aplicaciones si logra comprometer las credenciales de inicio de sesión SSO. Por lo tanto, se recomienda que las organizaciones implementen medidas de seguridad adicionales, como el uso de autenticación multifactorial y la monitorización continua de la actividad del usuario.

![image](https://user-images.githubusercontent.com/125692315/222617233-6d041362-2aac-4869-8f6f-41be9fbbb946.png)

______________________________________________________________________

![image](https://user-images.githubusercontent.com/125692246/222421652-d3626e2c-69c6-4703-a2eb-37a90fcaa328.png)

El inicio de sesión único federado (FSSO) es una variante del inicio de sesión único (SSO) que permite a los usuarios acceder a múltiples sistemas de software que pertenecen a diferentes organizaciones sin necesidad de tener una cuenta de usuario separada para cada uno de ellos. En otras palabras, FSSO permite a los usuarios autenticarse en un sistema de software y, a continuación, acceder a los sistemas de software de otras organizaciones que han acordado confiar en la autenticación del primer sistema.

FSSO se basa en tecnologías de federación de identidad, como SAML (Security Assertion Markup Language), que permiten a las organizaciones establecer acuerdos de confianza entre sí y compartir información de autenticación de forma segura. Cuando un usuario intenta acceder a un sistema de software federado, el sistema remite al usuario a su sistema de autenticación habitual para que se autentique. Si el usuario se autentica correctamente, el sistema de autenticación emite una "assertión" de seguridad al sistema federado que confirma la autenticación del usuario. A partir de entonces, el usuario puede acceder al sistema federado sin necesidad de volver a autenticarse.

Entre las ventajas del FSSO se incluyen la facilidad de uso para el usuario final, una mayor seguridad y privacidad para los datos de autenticación, y la reducción de la complejidad administrativa y los costos asociados con la gestión de múltiples cuentas de usuario. Sin embargo, el FSSO también presenta desafíos y riesgos de seguridad, como la necesidad de gestionar y mantener una infraestructura de federación de identidad y la posibilidad de ataques de phishing dirigidos a la red de confianza. Por lo tanto, se recomienda que las organizaciones implementen medidas de seguridad adicionales, como la autenticación multifactorial y la monitorización continua de la actividad del usuario, para mitigar estos riesgos.

![image](https://user-images.githubusercontent.com/125692315/222620999-e2dbe3dc-e7ae-4884-887f-159d76f3d66f.png)
______________________________________________________________________


![image](https://user-images.githubusercontent.com/125692246/222421714-6e024281-d35a-4f9c-a06f-25cc8f9f1b7d.png)

![Infografia autenticación de multifactor V2](https://user-images.githubusercontent.com/125692433/222453211-de5967b0-b342-434b-99d6-02c457560bc0.png)

La **autenticación de multi-factor** es un método que requiere que el usuario realice una múltiple autenticación la cual se puede dar en dos o más pasos con el fn de acceder a un recurso como lo es una aplicación, correo electrónico o una red privada virtual. El empleo de esta reduce la probabilidad de explotación de vulnerabilidades y materialización de riesgos. 


*Existen tres métodos de autenticación de multi-factor:*

1. Elementos que uno conoce como contraseñas y pin
2. Elementos que uno posee como un teléfono inteligente
3. Elementos que son inherentes como los biométricos: huella y reconocimiento por voz

______________________________________________________________________


![image](https://user-images.githubusercontent.com/125692246/222421753-adc8e292-81a5-46a7-9ca4-a63144df338f.png)

![Acceso basado en roles](https://user-images.githubusercontent.com/125692433/222461246-5b9528f2-5996-48f0-a69a-a599e2a38866.png)

El **control de acceso basado** en roles son los privilegios que tiene un usuario para acceder a los servicios y niveles de la red de acuerdo a la función o cargo que desempeña dentro de una organización. Bajo esta medida, las personas tendrán acceso limitado de acuerdo con las tareas específicas que desarrollan sin limitar las acciones necesarias para cumplir con sus responsabilidades. 

*Algunas opciones para el acceso de usuarios basado en roles puede ser:*

1. Contabilidad: acceso de un usuario final a las cuentas de la empresa
2. Técnicas: acceso a usuarios que desempeñan solo tareas técnicas dentro de la organización
3. Administrativo: acceso a usuarios que solo desempeñan tareas administrativas

______________________________________________________________________

![image](https://user-images.githubusercontent.com/125692246/222421824-4df64c98-0d0c-481e-a3a6-5ea6b617a385.png)

 
 - La gestión de identidades y accesos proporcionan medidas que deben ser implementadas en una organización con el fin de fortalecer los filtros requeridos a los usuarios cuando empleen recursos informáticos.
 - El control de acceso basado en roles es indispensable en la administración y auditoría de redes ya que facilita la vigilancia de ambientes distribuidos de tecnologías de la información. 


______________________________________________________________________


![image](https://user-images.githubusercontent.com/125692246/222421848-eadcef70-8f0c-425b-8a60-7dd21dd01e4e.png)


- US Department of Commerce. (2023). National Institute of Standars and Technology. https://csrc.nist.gov/glossary/term/role_based_access_control
- Microsoft Learn. (2023). Procedimiento para aprovisionar usuarios en AD DS. https://learn.microsoft.com/es-es/microsoft-identity-manager/mim-how-provision-users-adds
- Microsoft Learn. (2023). Desaprovisionamiento de dispositivos aprovisionados automáticamente. https://learn.microsoft.com/es-es/azure/iot-dps/how-to-unprovision-devices
- 



______________________________________________________________________
