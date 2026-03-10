<div align="center">

# **MicroControl App**

**Controla tu negocio**

Una aplicación móvil de gestión financiera e inventario, diseñada específicamente para optimizar la agilidad administrativa de las microempresas y comercios locales colombianos.


![inicio_app](https://drive.google.com/uc?export=view&id=15Zb6K0QDnuk9DDq3uPl4FUisoN5898xc)
</div>

## **Acerca del Proyecto**

MicroControl nace como una solución integral frente al caos administrativo que enfrentan diariamente los micronegocios, tales como cafeterías, tiendas de barrio y pequeños restaurantes. Es una realidad común que los dueños de estos establecimientos mezclen sus finanzas personales con las del local, o pierdan el control de su inventario debido a la falta de tiempo para realizar anotaciones manuales mientras atienden a su clientela.

Por esta razón, nuestra aplicación permite gestionar de manera unificada los ingresos, gastos, compras e inventarios, consolidando toda la información para generar reportes automáticos que facilitan la toma de decisiones. Todo esto se logra a través de una interfaz diseñada con un enfoque radical en la usabilidad, la cual no requiere que el usuario posea conocimientos contables previos.

## **Características Principales**

El Producto Mínimo Viable (PMV) ha sido estructurado mediante cinco módulos fundamentales y una característica de innovación clave:

* **Finanzas al Día (Ingresos, Compras y Gastos):** Permite llevar un registro centralizado de todas las transacciones financieras, abarcando desde el control de las ventas diarias y las compras, hasta el seguimiento de cuentas por cobrar y el pago a proveedores.  
* **Control de Inventario Inteligente:** El sistema descuenta y actualiza el stock de forma completamente automática tras cada venta registrada. Además, incluye un sistema de alertas visuales preventivas para notificar sobre niveles bajos de mercancía o productos próximos a su fecha de vencimiento.  
* **Reportes Automáticos:** Facilita el análisis del estado del negocio mediante la generación instantánea de Flujos de Caja y Estados de Resultados, basándose estrictamente en los datos ingresados previamente por el usuario.  
* **Registro por Voz:** Pensando en la agilidad que requiere la atención al cliente en tiempo real, la plataforma incorpora una herramienta de accesibilidad que permite registrar las transacciones financieras simplemente dictándolas al micrófono del dispositivo.

## **Tecnologías Utilizadas para el PMV**

* **Desarrollo Móvil:** Creada con **React Native** y gestionada a través del framework **Expo**, permitiendo un desarrollo ágil y multiplataforma (iOS y Android) desde una misma base de código.  
* **Persistencia de Datos:** Toda la información se almacena directamente en el dispositivo del usuario mediante **persistencia en caché y almacenamiento local** (AsyncStorage / SQLite), asegurando la privacidad de los datos financieros y la inmediatez en los tiempos de carga.  
* **Reconocimiento de Voz:** Integración de APIs nativas de dictado compatibles con los ecosistemas de Android y Apple.

## **Despliegue, instalacion y ejecución local**

Para Instalar la aplicación compilada directamente, puede dirigirse al asiguiente link https://bit.ly/47nuGUn

![qr](https://drive.google.com/uc?export=view&id=1LeChfu8tpVrvAJjjLKH10_3IdVTzT64n)

Para desplegar y ejecutar el PMV en un entorno de desarrollo local, asegúrate de tener Node.js instalado y sigue estas instrucciones:

1. **Clona este repositorio en tu máquina:**  
   git clone [https://github.com/Keevh/MicroControlApp.git](https://github.com/Keevh/MicroControlApp.git)

2. **Navega al directorio raíz del proyecto:**  
   cd MicroControlApp

3. **Instala las dependencias necesarias:**  
   npm install 

4. **Inicia el servidor de desarrollo de Expo:**  
   npx expo start

5. **Prueba la aplicación:** Una vez ejecutado el comando anterior, se generará un código QR en la terminal. Descarga la aplicación **Expo Go** en tu dispositivo móvil (disponible en Play Store y App Store) y escanea el código QR para compilar y visualizar la aplicación en tiempo real.

## **Modelo de Negocio**

El proyecto está estructurado para ser escalable comercialmente mediante un modelo *Freemium*, el cual se divide en tres niveles de acceso:

1. **Versión Gratuita:** Dirigida a facilitar la adaptación tecnológica del usuario, ofreciendo el registro básico de ingresos, compras y gastos operativos.  
2. **Suscripción Premium:** Constituye el núcleo de monetización de la aplicación, desbloqueando los reportes financieros avanzados y el control de inventario sin límites de capacidad.  
3. **Servicios Adicionales:** Planeada como una integración a futuro, esta característica permitirá a los negocios formalizados conectar el sistema directamente con el ecosistema de Facturación Electrónica de la DIAN.

## **Equipo de Desarrollo**

Este proyecto fue desarrollado como parte integral de la asignatura de **Ingeniería del Software II** en la **Universidad Industrial de Santander (UIS)**, bajo la dirección del docente Jeison Mauricio Delgado González.

**Integrantes:**

* **Yeison Steven Ovalle Manjarres** (Código: 2225115\)  
* **Kevin Alexander Salinas Paez** (Código: 2225107\)  
* **Kevin Andres Gallardo Robles** (Código: 2191918\)

<div align="center">

<i>Desarrollado para impulsar la digitalización y el crecimiento de las microempresas de nuestra región.</i>

</div>
