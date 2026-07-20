# SmartStock CR — Smart Inventory Management (Beta Universitaria)

Aplicación web demostrativa de gestión inteligente de inventarios para una PYME costarricense
ficticia dedicada a la fabricación de productos plásticos: **Plásticos del Valle S.A.** (Cartago).

> Proyecto académico. Todos los datos son simulados; la aplicación no realiza procesos
> empresariales reales ni genera documentos fiscales.

## Demo

Publicada con GitHub Pages en:
`https://jleonm506-create.github.io/SmartStock-CR/`

## Módulos

| Módulo | Contenido |
|---|---|
| Dashboard | 6 KPIs en vivo, gráfico de valor histórico, dona por categoría, compras vs. consumos, actividad reciente |
| Inventario | 50 productos, buscador inteligente, filtros dinámicos, ordenamiento y vista de tarjetas |
| Movimientos | 30 registros de entradas y salidas con responsable, motivo y estado de aprobación |
| Compras | 15 órdenes con recepciones parciales, saldos pendientes y avance |
| Proveedores | 10 proveedores con contacto, plazo de entrega y calificación |
| IASHA | Asistente de IA simulado con tarjetas inteligentes y recomendaciones de compra |
| Reportes | Generación simulada de PDF y Excel, rotación e inventario sin movimiento |
| Configuración / Perfil | Preferencias del sistema y datos del usuario |

## Cómo ejecutarlo localmente

No requiere instalación, servidor ni dependencias. Abre `index.html` en cualquier navegador
moderno. Todo el HTML, CSS y JavaScript está contenido en un solo archivo.

## Tecnologías

HTML5, CSS3 (variables y grid) y JavaScript sin librerías externas. Los gráficos son SVG
generados en tiempo de ejecución.

## Publicar en GitHub Pages

1. Sube `index.html` y `README.md` a la rama `main`.
2. Ve a **Settings → Pages**.
3. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. Guarda y espera un minuto: el sitio queda disponible en la URL de arriba.
