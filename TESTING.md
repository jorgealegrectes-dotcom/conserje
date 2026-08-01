# 🧪 Guía de Testing - Conserje

¡Gracias por probar la app Conserje! Esta guía te ayudará a validar todas las funciones.

## 📋 Checklist de Testing

### ✅ Funciones que DEBEN funcionar

#### 1. **Visualizar Cabañas Disponibles**
- [ ] Abres la app
- [ ] Se cargan las cabañas automáticamente
- [ ] Ves la lista de cabañas con sus detalles
- [ ] Puedes ver la disponibilidad de cada cabaña

#### 2. **Reservar una Cabaña**
- [ ] Seleccionas una cabaña disponible
- [ ] Aparece formulario de reserva
- [ ] Ingresas datos del turista
- [ ] Seleccionas fechas de entrada y salida
- [ ] Se confirma la reserva
- [ ] La cabaña aparece como "No disponible"

#### 3. **Check-in de Turistas**
- [ ] Encuentras la opción de "Check-in"
- [ ] Seleccionas un turista con reserva
- [ ] Se registra el check-in (fecha y hora)
- [ ] El estado cambia a "Turista hospedado"

#### 4. **Ver Disponibilidad**
- [ ] Hay una sección de "Disponibilidad"
- [ ] Muestra qué cabañas están libres/ocupadas
- [ ] Se actualiza cuando haces una reserva

---

### ⏳ Funciones EN DESARROLLO (esperado que NO funcionen completamente)

#### ❌ **Sistema de Pagos**
- Aún no está implementado
- Es normal que no funcione

#### ❌ **Búsqueda Avanzada**
- Aún está en desarrollo
- Es normal que tenga limitaciones

---

## 🐛 ¿Encontraste un bug?

Sigue estos pasos:

### 1. Anota los detalles:
- ¿Qué intentabas hacer?
- ¿Qué esperabas que pasara?
- ¿Qué pasó en realidad?
- ¿En qué navegador? (Chrome, Firefox, etc.)
- ¿En qué sistema operativo? (Windows, Mac, Linux)

### Ejemplo de bug bien reportado:
```
Título: "Error al reservar: la fecha no se guarda"

Pasos para reproducir:
1. Hago clic en "Reservar cabaña"
2. Selecciono una fecha
3. Hago clic en "Confirmar"
4. La reserva no se guarda

Resultado esperado: La reserva debería guardarse

Resultado actual: Aparece un error rojo
```

### 2. Crea un Issue en GitHub:
- Ve a: https://github.com/jorgealegrectes-dotcom/conserje/issues
- Haz clic en "New Issue"
- Pega los detalles
- Haz clic en "Submit new issue"

---

## 💡 ¿Quieres sugerir una mejora?

También puedes crear un issue con tus ideas:

### Ejemplo de sugerencia:
```
Título: "Feature request: Agregar notificaciones por email"

Descripción:
Sería útil recibir un email cuando:
- Se confirma una reserva
- Es hora del check-in
- Un turista cancela

Esto ayudaría a estar siempre informado.
```

---

## 🎯 Navegadores Recomendados

✅ **Chrome** - Totalmente compatible
⚠️ **Firefox** - No probado
⚠️ **Safari** - No probado
⚠️ **Edge** - No probado

Si usas otro navegador, repórtalo en un issue.

---

## 📊 Información útil

- **Versión actual**: Beta 1.0
- **Última actualización**: 2026-08-01
- **Desarrollador**: Jorge Alegre

---

## ¿Dudas?

Si no sabes cómo hacer algo:
1. Revisa el README.md
2. Abre un issue con tu pregunta
3. Alguien te ayudará

---

**¡Gracias por probar Conserje! Tu feedback es muy valioso.** 🙏
