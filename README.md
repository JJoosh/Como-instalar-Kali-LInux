# installKaili

# Instalación de Kali Linux en Windows y Mac M1

Instalar Kali Linux en Windows y en una Mac con procesador M1 puede ser un proceso diferente debido a las diferencias en las arquitecturas y los sistemas operativos. A continuación, encontrarás una guía para cada plataforma:

## Instalación de Kali Linux en Windows

**Descargar Kali Linux para Windows:**

1. Ve al [sitio web oficial de Kali Linux](https://www.kali.org/downloads/).
2. Descarga la versión de "Kali Linux Windows Application" que sea compatible con tu sistema (32 bits o 64 bits).

**Instalar la Aplicación de Kali Linux en Windows:**

1. Ejecuta el archivo descargado para iniciar la instalación.
2. Sigue las instrucciones del instalador para completar la instalación en tu sistema.

**Configurar Kali Linux en Windows:**

1. Una vez instalado, ejecuta la aplicación.
2. Configura un usuario y contraseña para Kali Linux.
3. La aplicación proporcionará un entorno de Kali Linux virtualizado en tu sistema Windows.

**Usar Kali Linux en Windows:**

Ahora puedes utilizar Kali Linux directamente desde la aplicación que instalaste en Windows.

## Para más ayuda puedes consultar este video
[Como instalar Kali Linux](https://youtu.be/TDmRD4FU4a8?si=JShayp5fGQ9WaXBh) 


# Instalación de Kali Linux en Mac M1 (Apple Silicon) utilizando UTM

La instalación de Kali Linux en una Mac con procesador M1 (Apple Silicon) requiere el uso de una máquina virtual y una aplicación de virtualización como UTM (Universal Type Machine). A continuación, te proporciono una guía paso a paso:

## Paso 1: Descargar Kali Linux ARM64

1. Desde el sitio oficial de Kali Linux, descarga la imagen ARM64: [https://www.kali.org/docs/arm/kali-linux-arm-images/](https://www.kali.org/docs/arm/kali-linux-arm-images/).

## Paso 2: Instalar UTM en tu Mac M1

1. Ve a la App Store en tu Mac M1.
2. Busca "UTM" y descarga la aplicación UTM (Universal Type Machine).

## Paso 3: Crear una Máquina Virtual en UTM

1. Abre la aplicación UTM.
2. Haz clic en "Nueva VM" para crear una nueva máquina virtual.
3. Selecciona "Linux" como tipo de sistema operativo.
4. En "Arquitectura", elige "ARM" y selecciona "cortex-a72" como modelo de CPU (que es la arquitectura ARM utilizada en Mac M1).
5. En "Imagen", selecciona la imagen de Kali Linux ARM64 que descargaste anteriormente.

## Paso 4: Configurar la Máquina Virtual

1. Asigna suficiente RAM y espacio de almacenamiento según tus necesidades (recomendado al menos 2 GB de RAM para Kali Linux).
2. Configura la red y otros ajustes según tus preferencias.
3. Asegúrate de que la imagen de Kali Linux esté seleccionada como medio de arranque.

## Paso 5: Instalar Kali Linux

1. Inicia la máquina virtual.
2. Sigue las instrucciones de instalación de Kali Linux dentro de la máquina virtual.

## Paso 6: Configurar Kali Linux

1. Una vez instalado Kali Linux, configura el sistema dentro de la máquina virtual según tus preferencias.
2. Actualiza y configura las herramientas de seguridad según sea necesario.

## Paso 7: Usar Kali Linux en tu Mac M1

1. Ejecuta la máquina virtual UTM para usar Kali Linux en tu Mac M1.

Recuerda que esta configuración permite ejecutar Kali Linux en una máquina virtual en tu Mac M1 y puede tener algunas limitaciones de rendimiento en comparación con una instalación nativa. La elección entre la instalación nativa en Windows o la instalación en una máquina virtual en una Mac M1 dependerá de tus preferencias y necesidades específicas.


