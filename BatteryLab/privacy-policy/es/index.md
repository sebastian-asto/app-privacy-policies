# Política de Privacidad de Battery Runtime Calculator

**Fecha de vigencia:** 3 de agosto de 2026

**Versión:** 1.0

## 1. Identidad del desarrollador

Battery Runtime Calculator es desarrollada y publicada por **Sebastian Asto**, desarrollador ubicado en **Perú**.

## 2. Descripción de la aplicación

Battery Runtime Calculator es una calculadora técnica que estima la autonomía de una batería a partir de valores proporcionados por el usuario. La aplicación permite considerar la capacidad de la batería, el consumo promedio del dispositivo, la eficiencia del sistema, la capacidad utilizable y un margen de seguridad.

Los resultados son estimaciones técnicas. La autonomía real puede variar por factores como las condiciones de uso, la temperatura, el estado de la batería, las tolerancias de los componentes y los cambios en el consumo del dispositivo.

## 3. Información que recopila Battery Runtime Calculator

Battery Runtime Calculator no recopila ni transmite fuera del dispositivo datos personales, datos del dispositivo ni datos sobre el uso de la aplicación. No solicita nombre, correo electrónico, número de teléfono, dirección, credenciales ni identificadores del dispositivo. Tampoco ofrece cuentas ni inicio de sesión.

## 4. Datos ingresados por el usuario

Para realizar un cálculo, el usuario puede ingresar o seleccionar:

- capacidad nominal de la batería y su unidad;
- consumo promedio del dispositivo y su unidad;
- porcentaje de eficiencia del sistema;
- porcentaje de capacidad utilizable; y
- activación y porcentaje del margen de seguridad.

Estos son valores técnicos. Battery Runtime Calculator los utiliza únicamente para calcular y mostrar una estimación de autonomía.

## 5. Procesamiento local

Los valores ingresados y los resultados se procesan exclusivamente en el dispositivo. Battery Runtime Calculator no los envía al desarrollador ni a servidores de terceros.

Los datos del cálculo se mantienen temporalmente en la memoria de la aplicación durante la sesión. No se guardan de forma persistente y pueden perderse al cerrar o reiniciar la aplicación, o cuando el sistema operativo finaliza su proceso.

## 6. Acceso a Internet

Battery Runtime Calculator funciona completamente sin conexión a Internet. La versión Android de producción no solicita el permiso de Internet y el código de la aplicación no realiza solicitudes de red.

Los manifiestos Android de desarrollo (`debug` y `profile`) incluyen el permiso de Internet exclusivamente para las herramientas de desarrollo de Flutter, como depuración y recarga en caliente. Ese permiso no forma parte de la versión de producción destinada a Google Play.

## 7. Permisos del dispositivo

Battery Runtime Calculator no solicita permisos sensibles o de tiempo de ejecución para acceder a la ubicación, cámara, micrófono, contactos, archivos, almacenamiento compartido ni Bluetooth.

El paquete Android de producción puede incluir componentes técnicos estándar de Flutter y AndroidX, entre ellos un permiso interno de nivel `signature` asociado a receptores protegidos y una declaración de visibilidad para aplicaciones capaces de procesar texto. Estos elementos no conceden a Battery Runtime Calculator acceso a los datos sensibles indicados ni se utilizan para transmitir información fuera del dispositivo.

## 8. Almacenamiento local

Battery Runtime Calculator no utiliza bases de datos locales, `SharedPreferences`, almacenamiento seguro ni archivos para conservar los valores introducidos, los resultados, el idioma o el tema seleccionados. Estas opciones existen únicamente en memoria mientras la aplicación está en ejecución.

## 9. Servicios y componentes de terceros

Battery Runtime Calculator utiliza Flutter para su interfaz y funcionamiento, `flutter_localizations` para la localización e `intl` para el formato local de números. La versión Android también incorpora componentes estándar de compatibilidad y ciclo de vida de AndroidX como parte de la plataforma Flutter.

El uso observado de estos componentes en Battery Runtime Calculator se limita a la interfaz, localización, formato numérico y soporte de la aplicación. No se han configurado servicios en línea ni SDK de terceros para recopilar o transmitir datos.

Battery Runtime Calculator no integra Firebase, AdMob, servicios de autenticación, plataformas sociales ni otros servicios externos.

## 10. Publicidad, analítica e informes de errores

Battery Runtime Calculator no muestra publicidad y no utiliza servicios de analítica, seguimiento, elaboración de perfiles ni reporte remoto de errores o fallos.

## 11. Seguridad

Battery Runtime Calculator reduce la exposición de los datos técnicos ingresados al procesarlos localmente, sin transmitirlos y sin conservarlos en almacenamiento persistente controlado por la aplicación. La protección del dispositivo y del acceso físico depende de las medidas de seguridad del sistema operativo y de las configuradas por el usuario.

## 12. Privacidad de menores

Battery Runtime Calculator es una herramienta técnica de uso general y no está diseñada para recopilar información personal de menores. Dado que la aplicación no recopila ni transmite datos personales de sus usuarios, tampoco realiza una recopilación intencional de datos personales de menores.

## 13. Cambios en esta política

Esta política se actualizará si cambia la forma en que Battery Runtime Calculator procesa información o si se incorporan funciones como publicidad, analítica, cuentas, servicios en línea, almacenamiento persistente o nuevos SDK. La versión actualizada indicará su nueva fecha de vigencia.

## 14. Contacto

Para consultas sobre esta política o sobre la privacidad en Battery Runtime Calculator, puede escribir a:

**Sebastian Asto**  
**Correo electrónico:** marseapps@gmail.com  
**País:** Perú
