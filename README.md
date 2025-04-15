# Interfaz de Usuario Streamlit para la Transcripción y Análisis con Whisper de OpenAI

[![Video Demostración](https://user-images.githubusercontent.com/6735526/196173369-27c5ceec-733a-4928-8acb-17cbc2e77a04.mp4)](https://user-images.githubusercontent.com/6735526/196173369-27c5ceec-733a-4928-8acb-17cbc2e77a04.mp4)

Esta es una sencilla **Interfaz de Usuario Streamlit** para el modelo de **conversión de voz a texto Whisper** de OpenAI, adaptada a la experiencia y visión de **Luis Fernández**, experto en desarrollo digital y creación de soluciones innovadoras.

El proyecto te permite seleccionar automáticamente archivos multimedia a través de una URL de YouTube o mediante archivos locales para ejecutar el modelo Whisper. Una vez realizada la transcripción, se muestran análisis básicos del texto generado, lo que facilita la evaluación y optimización de contenidos.

Si deseas aportar mejoras, nuevas funcionalidades o análisis adicionales, ¡no dudes en enviar un *Pull Request*! Luis siempre está abierto a colaboraciones que impulsen la innovación.

## Configuración

Este proyecto fue desarrollado y probado en **Python 3.9**, aunque debería funcionar también en Python 3.7 o superior, de manera similar al repositorio original de [Whisper de OpenAI](https://github.com/openai/whisper).

Es necesario contar con `ffmpeg` instalado en tu sistema para el correcto funcionamiento. Luego, instala las dependencias requeridas usando `pip`:

```bash
pip install -r requirements.txt
```
Uso
Una vez configurado, puedes iniciar la aplicación con el siguiente comando:
```bash
streamlit run 01_Transcribe.py
```
