# ⚓ MKN Magazin - Digital Edition

Bienvenido al repositorio de despliegue de **MKN Magazin**. Este sitio utiliza un motor de renderizado basado en `HTML5 Canvas` para ofrecer una experiencia de lectura inmersiva (Flipbook).

## 🚀 Despliegue Rápido

1. **Subir PDF:** Guarda tu edición mensual en la raíz con el nombre `magazine.pdf`.
2. **Commit:** `$ git add . && git commit -m "mkn publish: Edición 2026.02"`
3. **Push:** `$ git push origin main`

## 🛠 Comandos de la Gema `mkn-magazine`

Si tienes instalada nuestra gema de gestión, puedes usar los siguientes comandos:

* `mkn status` : Verifica la integridad del PDF y metadatos.
* `mkn build --flipbook` : Prepara los assets para el visor web.
* `mkn publish --target github` : Sube automáticamente los cambios a este repo.

## 📁 Estructura del Proyecto
```text
├── index.html          # Visor de Flipbook (Core)
├── magazine.pdf        # El archivo de la revista (Actualizar aquí)
└── README.md           # Estas instrucciones
