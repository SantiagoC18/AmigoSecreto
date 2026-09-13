# 🎁 Amigo Secreto Rifa

> Juego interactivo de Amigo Secreto en tiempo real con asignación aleatoria segura 🎲

---

## ✨ ¿Qué es esto?

Es una aplicación web para realizar sorteos de **Amigo Secreto** con un toque divertido. Los participantes seleccionan una tarjeta numerada y descubren de forma instantánea a quién les toca regalar — todo en tiempo real gracias a Firebase.

## 🎯 Características Principales

- 🃏 **Tablero de N número de tarjetas segun se requiera** — Cada una con un número único
- 🎲 **Asignación aleatoria segura** — Algoritmo de Derangement que garantiza que NADIE se toque a sí mismo
- ⏱️ **Sincronización en tiempo real** — Cuando una persona toma una tarjeta, todas las demás ven que ya está tomada
- 🎊 **Experiencia divertida** — Animaciones de volteo 3D, lluvia de confeti y modales elegantes
- 📱 **Totalmente responsive** — Funciona perfectamente en celulares, tabletas y computadoras
- 🔒 **Prevención de doble selección** — Cada tarjeta solo se puede destapar una vez
- 💾 **Persistencia en Firebase** — Todo se guarda en la nube, no se pierde nada

## 🚀 ¿Cómo se usa?

1. **Abre el archivo** `index.html` en tu navegador favorito
2. Espera a que el organizador inicie el juego
3. Una vez activado, verás las **Las tarjetas numeradas** 🔢
4. **Escoge tu número de la suerte** y haz clic/toca la tarjeta
5. Confirma la selección en el modal ✅
6. **¡Listo!** Aparecerá el nombre de tu Amigo Secreto con confeti incluido 🎉
7. **Anota el nombre** y ¡prepara tu regalo sorpresa! 🎁

## 🛠️ Tecnologías

| Tecnología | Uso |
|------------|-----|
| 🌐 **HTML5 + CSS3** | Estructura y estilo visual |
| ⚡ **Tailwind CSS** | Diseño moderno y responsive |
| 🎨 **SweetAlert2** | Modales bonitos y amigables |
| 🎊 **Canvas Confetti** | La lluvia de confeti al destapar |
| 🔥 **Firebase Realtime Database** | Sincronización en tiempo real entre todos los participantes |
| 📜 **JavaScript Vanilla** | Lógica del juego sin dependencias pesadas |

## 🎨 Diseño Visual

- Fondo con **gradiente morado/azul** súper moderno
- Tarjetas rojas con **borde dorado** estilo casino/rifa
- **Animación 3D** de volteo al seleccionar cada tarjeta
- Paleta de colores: rojo, rosa, ámbar/dorado — ¡vivos y festivos!

## 📋 Reglas del Juego

1. Cada persona solo puede seleccionar **UNA** tarjeta
2. Las tarjetas ya tomadas aparecen **bloqueadas** (🔒)
3. La asignación es **totalmente aleatoria** y no se ve hasta que destapas tu carta
4. **Recuerda anotar o memorizar** el nombre que te salió — es un secreto 🤫

## 🧠 ¿Cómo funciona por dentro?

El algoritmo de **Derangement (Desordenamiento Perfecto)** asegura:

```
✅ Se mezcla la lista al azar
✅ Ninguna persona queda en su misma posición original
✅ Garantizado: nunca te toca regalarte a ti mismo
```

## 🤝 Contribuciones

Si quieres mejorar el juego, ¡eres bienvenido! Solo recuerda:
- Las asignaciones siguen siendo anónimas hasta destaparse
- La lógica de sincronización en tiempo real se mantenga

---

### 🎅 ¡Feliz Juego y que les toque regalar a alguien genial! 🎁
