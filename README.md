# 🚀 Limpiador de Caché de Red

Un script de automatización simple para Windows diseñado para refrescar la conexión a internet, liberar y renovar la dirección IP, y vaciar la caché DNS para solucionar problemas de conectividad.

## 📝 Código del Script

```cmd
@echo off
title Limpiar cache
ipconfig /release
ipconfig /renew
ipconfig /flushdns
echo Red refrescada con exito. Gracias por utilizar ''Limpiar cache'' de rAfar.
pause
```



## 🔍 Componentes del Script

* 🚪 **ipconfig /release**: Libera la dirección IP actual asignada por tu router.
* 🔄 **ipconfig /renew**: Solicita una nueva dirección IP al router.
* 🧹 **ipconfig /flushdns**: Vacía la caché de resolución de nombres DNS para corregir páginas web que no cargan.

---
 ## 💻 Creado por rTech.
