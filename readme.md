

# 🔥 INSTALACIÓN POR TERMUX
* Instala **Termux** [aquí](https://f-droid.org/repo/com.termux_118.apk)

> [!NOTE]  
> Copia los comandos uno por uno, **no los pegues todos juntos**.

```bash
apt-get update -y && pkg upgrade -y && pkg update -y && pkg install nodejs -y && pkg install nodejs-lts -y && pkg install ffmpeg -y && pkg install wget -y && pkg install tesseract -y && pkg install git -y
termux-setup-storage
cd /sdcard && git clone https://github.com/Martinez2319/Martinez-base-main
cd Martinez-base-main
node index
🔥 REACTIVAR EN CASO DE DETENERSE EN TERMUX

Si después de instalar el bot en Termux se detiene (pantalla en blanco, pérdida de conexión a Internet, reinicio del dispositivo), sigue estos pasos:
1. Abre Termux y navega al directorio del bot:

    cd Martinez-base-main

2. Inicia el bot nuevamente:

    node index
