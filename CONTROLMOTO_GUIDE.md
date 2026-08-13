# 🚔 ControlMoto - Sistema de Multas por Infracción de Casco

Una aplicación web moderna para registrar, gestionar y controlar multas por no uso de casco en motociclistas. Sistema completo con generación de boletas, estadísticas y gestión de pagos.

## ✨ Características Principales

### ✅ Funcionalidades Implementadas

- 📝 **Registrar Infracciones** - Formulario completo para reportar motociclistas sin casco
- 📋 **Gestión de Multas** - Ver, marcar como pagadas y eliminar multas
- 📊 **Estadísticas en Tiempo Real** - Total de multas, pagadas, pendientes y monto recaudado
- 📥 **Descargar PDF** - Generar boleta de infracción descargable
- 👤 **Datos del Infractor** - Registro completo con placa, cédula, teléfono, ubicación
- 🎯 **Infractores Frecuentes** - Top de placas con más infracciones
- 💾 **Datos en Sesión** - Almacenamiento en tiempo real

### ⏳ Funcionalidades En Desarrollo

- 🗄️ **Base de Datos** - Persistencia de multas (próximamente)
- 📧 **Notificaciones Email** - Alertas a infractores (próximamente)
- 📸 **Upload de Foto** - Evidencia fotográfica (próximamente)
- 🔗 **Integración de Placas** - Verificación en registro nacional (próximamente)

---

## 🚀 Inicio Rápido

### Para Descargar:
1. Ve a: https://github.com/jorgealegrectes-dotcom/conserje/tree/feature/traffic-violation-app
2. Descarga: `controlmoto.html`
3. Abre en Chrome

### Para Ejecutar:
```bash
# Hacer clic derecho en controlmoto.html
# Seleccionar "Abrir con" → "Google Chrome"
```

---

## 📋 Guía de Usuario

### 1️⃣ **Registrar Nueva Infracción**

Completa el formulario con:

**Datos de la Motocicleta:**
- **Placa**: ABC-123 (requerido)
- **Tipo de Infracción**: 
  - No usar casco de seguridad
  - Casco defectuoso o inadecuado
  - Casco desabrochado

**Datos del Conductor:**
- **Nombre Completo**: (requerido)
- **Cédula**: (requerido, mín 5 dígitos)
- **Teléfono**: (opcional)

**Detalle de la Infracción:**
- **Ubicación**: Calle/Avenida, intersección (requerido)
- **Hora**: Hora exacta de la infracción (requerido)
- **Observaciones**: Detalles adicionales (opcional)

**Después de llenar:**
- Haz clic en "🚔 Generar Multa"
- Se crea automáticamente y se asigna número
- Monto: $500 (configurable)

---

### 2️⃣ **Ver Multas Registradas**

En la sección "📋 Mis Multas" verás:

- **Número de Multa**: ID único (#1000, #1001, etc)
- **Fecha y Hora**: Cuándo se registró
- **Estado**: Pendiente o Pagada (badge de color)
- **Datos Completos**: Placa, conductor, cédula, ubicación
- **Monto**: $500 por infracción
- **Acciones**:
  - ✓ Marcar Pagada
  - 📥 Descargar PDF
  - 🗑️ Eliminar

---

### 3️⃣ **Marcar Como Pagada**

1. Busca la multa en el listado
2. Haz clic en "✓ Marcar Pagada"
3. Se cambia el estado a "Pagada"
4. Se registra automáticamente la fecha de pago

---

### 4️⃣ **Descargar Boleta (PDF/TXT)**

1. Selecciona la multa
2. Haz clic en "📥 Descargar PDF"
3. Se descarga un archivo con formato de boleta oficial
4. Contiene:
   - Número de multa
   - Datos del infractor
   - Detalles de la infracción
   - Monto y estado
   - Instrucciones de pago

---

### 5️⃣ **Ver Estadísticas**

En la sección "📊 Estadísticas" encontrarás:

**Tarjetas de Resumen:**
- 📊 Total de Multas registradas
- ✓ Multas Pagadas
- ⏳ Multas Pendientes
- 💰 Monto Total Recaudado

**Infractores Más Frecuentes:**
- Ranking de placas con más infracciones
- Número de infracciones por placa

---

## 🎮 Ejemplo Práctico

### Escenario: Registrar infracción

```
1. Ves un motociclista sin casco en Calle Principal y Calle 5
2. Abres ControlMoto
3. Haz clic en "📝 Registrar Infracción"
4. Completas:
   - Placa: ABC-123
   - Nombre: Juan Pérez
   - Cédula: 12345678
   - Teléfono: +34 912345678
   - Ubicación: Calle Principal y Calle 5
   - Hora: 14:30
   - Tipo: No usar casco de seguridad
   - Observaciones: Motociclista circulaba sin casco

5. Haz clic en "🚔 Generar Multa"
6. Se genera Multa #1000
7. Haz clic en "📥 Descargar PDF"
8. Descarga la boleta para entregar
```

---

## 📱 Requisitos del Sistema

| Requisito | Detalle |
|-----------|---------|
| **Navegador** | Chrome (recomendado), Firefox, Safari, Edge |
| **Sistema Operativo** | Windows, Mac, Linux |
| **Conexión** | No requiere conexión a internet |
| **Almacenamiento** | Menos de 1MB |
| **Instalación** | NO requiere instalación |

---

## 🌐 Navegadores Recomendados

| Navegador | Estado | 
|-----------|--------|
| 🔵 Chrome | ✅ Totalmente compatible |
| 🦊 Firefox | ⚠️ No probado |
| 🧭 Safari | ⚠️ No probado |
| 🔵 Edge | ⚠️ No probado |

---

## 🐛 Soluciones a Problemas Comunes

### ❌ "No puedo abrir el archivo"
- Asegúrate de usar Chrome
- Intenta hacer clic derecho → "Abrir con" → Chrome

### ❌ "El formulario no guarda datos"
- Los datos se guardan en la sesión actual
- Si cierras y abres la página, se pierden (próximamente habrá persistencia)

### ❌ "No puedo descargar el PDF"
- Verifica que el navegador permita descargas
- Intenta en Chrome

### ❌ "Tengo otro error"
- Abre un Issue en GitHub
- Describe exactamente qué pasó

---

## 💡 Casos de Uso

### Para Policía de Tránsito:
- ✅ Registrar infracciones en tiempo real
- ✅ Generar multas automáticas
- ✅ Descargar boletas
- ✅ Seguimiento de pagos

### Para Ciudades/Municipios:
- ✅ Reportar infracciones
- ✅ Hacer cumplir normas de seguridad
- ✅ Recaudar multas
- ✅ Analizar tendencias

### Para Empresas de Transporte:
- ✅ Monitorear conductores
- ✅ Registrar infracciones
- ✅ Fomentar cumplimiento normativo

---

## 📊 Información del Sistema

- **Versión:** Beta 1.0
- **Tipo:** Aplicación Web HTML5
- **Monto Multa:** $500 (configurable)
- **Almacenamiento:** Sesión actual
- **Plataformas:** Windows, Mac, Linux

---

## 🎯 Próximos Pasos

1. **Descargar:** Sigue los pasos de "Inicio Rápido"
2. **Probar:** Registra algunas infracciones
3. **Explorar:** Ve todas las funciones
4. **Reportar:** Si encuentras algo, abre un Issue
5. **Sugerir:** ¿Ideas? ¡Nos encantaría escucharte!

---

## 📞 Soporte

### ¿Tienes preguntas?
- Lee esta guía completa
- Abre un Issue en GitHub

### ¿Encontraste un bug?
- Ve a Issues
- Haz clic en "New Issue"
- Describe el problema

### ¿Tienes una idea?
- Abre un Issue
- Describe tu sugerencia
- ¡Nos encantaría implementarla!

---

**¡Esperamos que ControlMoto te ayude a mejorar la seguridad vial!** 🚔✨

Última actualización: 2026-08-13
Versión: Beta 1.0
