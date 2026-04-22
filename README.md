# New-Master-Emerald

Proyecto de dibujo con p5.js.

## Ejecutar en el navegador

1. Abre una terminal dentro de este proyecto.
2. Inicia un servidor local:

```bash
python3 -m http.server 8000
```

3. Abre esta URL en tu navegador:

```text
http://localhost:8000
```

## Cámara

La aplicación usa la cámara del navegador para detectar el rostro con MediaPipe FaceMesh. Si el navegador pide permiso, acéptalo para que el dibujo siga tu cara.