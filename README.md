# README.md - Pruebas Automatizadas de Calculadora en Android

## Ejecución de Pruebas Automatizadas en una Calculadora para Sistema Operativo Android

### Precondiciones

Antes de comenzar, asegúrate de tener instalados los siguientes requisitos previos en tu máquina:

- **Java JDK** (versión 8 o superior).  
  Descarga e instala desde [Java JDK](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html).
  
- **Android Studio**.  
  Descarga e instala desde [Android Studio](https://developer.android.com/studio).

- **Vysor** (opcional, para controlar tu dispositivo Android desde el escritorio).  
  Descarga desde [Vysor](https://www.vysor.io/).

- Un dispositivo Android físico o un emulador configurado en Android Studio.

- **Node.js** y **npm** (Node Package Manager).  
  Descarga desde [Node.js](https://nodejs.org/).

---

### Pasos para Configurar y Ejecutar

1. **Clonar el repositorio**

   Clona este repositorio en tu máquina local. Ejecuta el siguiente comando en tu terminal:

   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```

   Navega al directorio del proyecto:

   ```bash
   cd tu-repositorio
   ```
   Abre el repositorio en VSCode: 
   ```bash
   code .
   ```

1. **Instalar las dependencias**

   Instala las dependencias necesarias ejecutando:

   ```bash
   npm install
   ```

2. **Instalar Appium como dependencia de desarrollo**

   Appium se utiliza para la automatización de pruebas en aplicaciones móviles. Instálalo con el siguiente comando:

   ```bash
   npm install --save-dev appium
   ```

3. **Configurar Appium y tu dispositivo**

   - Inicia **Appium Server**. Puedes instalar Appium Desktop o iniciar Appium desde la línea de comandos.
   - Conecta tu dispositivo Android físico o inicia un emulador.
   - Habilita **Depuración USB** en tu dispositivo.

4. **Ejecutar las pruebas**

   Ejecuta las pruebas automatizadas con el siguiente comando:

   ```bash
   npx wdio
   ```

   Este comando ejecutará el script definido en el proyecto para probar la funcionalidad de la calculadora.

---

### Notas

- Asegúrate de que tu dispositivo o emulador tenga la aplicación de la calculadora instalada y sea accesible desde Appium.
- Si tienes problemas para conectar tu dispositivo o emulador, verifica que `adb` (Android Debug Bridge) esté configurado correctamente en tu entorno.

---

### Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un **Pull Request** o crea un **Issue** para discutir posibles mejoras.

---

¡Listo! Ahora puedes ejecutar tus pruebas automatizadas en Android. 🎉
