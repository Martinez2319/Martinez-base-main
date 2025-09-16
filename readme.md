# 🔥INSTALACIÓN POR TERMUX.
* Instala el termux [aqui](https://f-droid.org/repo/com.termux_118.apk)

> [!NOTE]
> Copia los códigos uno por uno, no los pegues todos juntos a la vez.

```bash
apt-get update -y && pkg upgrade -y && pkg update -y && pkg install nodejs -y && pkg install nodejs-lts -y && pkg install ffmpeg -y && pkg install wget -y && pkg install tesseract -y && pkg install git -y
```

```bash
termux-setup-storage
```

```bash
cd /sdcard && git clone https://github.com/Martinez2319/Martinez-base-main.git
```

```bash
cd Martinez-base-main
```

```bash
node index
```
# 🔥ACTIVAR EN CASO DE DETENERSE EN TERMUX

Si después de instalar el bot en Termux se detiene (pantalla en blanco, pérdida de conexión a Internet, reinicio del dispositivo), sigue estos pasos:

1. Abre Termux y navega al directorio del bot:
    ```bash
    cd Martinez-base-main
    ```

2. Inicia el bot nuevamente:
    ```bash
    node index
    ```
