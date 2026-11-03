# Sosiego · Mejoras aplicadas a los prototipos

Origen: hoja *Hallazgos* de `Matriz_y_Hallazgos_Idea_1.xlsx` (entrevista anterior, Gustavo y Salim Ramírez).
Los números entre paréntesis (#) son el **N°** de esa hoja.

Archivos: `web.html` (landing), `app.html` (app móvil, láminas e individual), `kit-3d.html` (visor 3D).
Se abren con doble clic; no necesitan servidor.

## Visor 3D (`kit-3d.html`)

| Hallazgo | Cambio |
|---|---|
| #48, #49 Solo se movía en 2D; quiere girar 360° | Arrastrar con un dedo o con el botón izquierdo **gira el objeto 360°** (y lo inclina, con límites para no ver bajo el piso), con inercia suave. El desplazamiento pasa a **dos dedos / clic derecho / Mayús+arrastrar**; pellizco y rueda siguen haciendo zoom. Teclado: Mayús+flechas giran; doble clic o `R` restablece (vuelve por el camino más corto). Aviso breve «Arrastra para girar 360°» que desaparece al interactuar. |
| #10, #65 Nombres con poca identidad | Cada dispositivo muestra bajo su nombre una descripción de una línea (p. ej. «Base de carga nocturna del celular»). |
| #71, #73, #85 Nido vs. cargador | Texto del Nido y aviso al dejar el celular: «Cargando el celular · reloj tenue de noche». El modelo 3D no cambió. |

## Sitio web (`web.html`)

| Hallazgo | Cambio |
|---|---|
| #70, #87 La landing no dice por qué comprar | Nueva estructura: hero con beneficio concreto → **sección de la Almohada Nube como producto estrella** (con ejemplo visual de ventana y hora límite) → cómo funciona → kit → Nido → noche → app → **precios** → problema, público, evidencia, privacidad, FAQ. El problema y la evidencia bajan; el kit y los precios suben. Transiciones sutiles al hacer scroll (respetan «reducir movimiento»). |
| #69, #86, #18, #19 Kit Esencial poco atractivo, Orbe redundante | **Kit Esencial = Nido + Alba + Almohada Nube** (el Orbe sale del kit de entrada y queda en el Completo). Actualizado en web y app (tienda, carrito, pago, pedidos). |
| #15 Precio y ahorro no destacan / parecen tabla | Precio en caja con relieve y color distinto; el ahorro es una etiqueta aparte. Se quitó la línea «Suelto: …» de la cabecera. |
| #80 ¿Cómo se fijaron los precios? | Nota «¿Cómo calculamos el ahorro?»: compara contra la suma de dispositivos sueltos de Sosiego; aclara que aún no hay comparación verificada con la competencia. |
| #14, #66, #79 Confusión con estudiantes de medicina | El dato 77,7 % se presenta como «estudiantes de medicina» con una aclaración: Sosiego es para cualquier persona que estudia o trabaja. La franja de cifras ya no abre con ese estudio; se añaden chips «Quien estudia / trabaja / hace ambas». |
| #57, #68, #77, #78 Una sola alarma y hora límite | Explicación en la sección Nube y 3 preguntas nuevas en FAQ (cómo funciona, qué pasa si el sueño ligero llega tarde, qué pasa si uso varias alarmas). |
| #72, #63, #82 Compatibilidad con otras marcas | FAQ: hoy solo dispositivos Sosiego; otras marcas «en evaluación», sin prometerlo. |
| #73, #71, #85 Nido como cargador | Nido: viñeta «Carga tu celular mientras duerme» (base inalámbrica magnética) y FAQ. |
| #74 Calibración de la Nube | FAQ: qué mide y cómo se calibra (45 s, boca arriba). |
| #76, #83 Smartwatch y Salud | FAQ con lo que permite la app (ver abajo). |
| #8, #9, #10, #65 Identidad y nombres | Lema bajo el logotipo («para dormir en calma») y descriptor en cada dispositivo del kit. |
| #20 Alba no alumbra todo el cuarto | Solo texto: «adaptador de techo opcional». No hay modelo ni precio. |

## App móvil (`app.html`)

| Hallazgo | Cambio |
|---|---|
| #6 Ilustraciones mejores (tipo Duolingo) | Mascota **Luna** (luna con gorro de dormir) en bienvenida, inicio de sesión, kit listo, sesión completada, calma rápida y pedido confirmado. |
| #7 Juntar términos y registro | La casilla «Acepto los términos y la política de privacidad» está en la misma pantalla de crear cuenta; el botón dice «Crear cuenta y continuar». |
| #5 Carga visual | Subtítulos más cortos en cuenta, metas, permisos, kit listo y test de hábitos. |
| #38 Explicar permisos y Nido en una línea | Bluetooth, Notificaciones, Salud y Nido ahora dicen para qué sirven. |
| #67 Metas que parecen tratamiento | Metas reescritas («Bajar el ritmo antes de dormir», «Tener noches más tranquilas») y aviso de alcance no clínico en la misma pantalla. |
| #62, #81 Configuración compleja | Pantalla nueva **17b «Tu noche en un toque»**: configuración automática, perfiles predefinidos y opción manual avanzada. |
| #64 Poco diferenciado de alarmas nativas | En «Despertar suave»: «Lo que una alarma común no hace» (sueño ligero, luz de Alba, sin posponer). |
| #68, #78 Hora límite | «Hora límite 06:45 · suena sí o sí, nunca después». |
| #75 «Escaneo corporal» | Aclarado como audio de relajación que no mide nada. |
| #83, #76 Smartwatch y Salud | Pantalla nueva **74b «Reloj y Salud»**: lectura de horas de sueño, controles rápidos del reloj, detección automática marcada «Próximamente». |
| #84 Ronquidos y sonidos | Pantalla nueva **74c «Sonidos de la noche»**: opcional, apagado por defecto, con consentimiento y aclaración de que no es diagnóstico. Enlazada desde Privacidad. |
| #72, #63, #82 Otras marcas | En «Añadir dispositivo»: «Otras marcas · Próximamente». |
| #71, #73, #85 Nido | Detalle del Nido con **Carga magnética** y **Reloj tenue de noche**. |
| #10 Nombres | «Tu kit está listo» muestra qué hace cada dispositivo. |

Las pantallas nuevas se llaman 17b, 74b y 74c para no renumerar las 79 existentes; aparecen en ambos diseños (individual y láminas, esta última al final).

## Decisiones que conviene validar con el equipo

- **Precios nuevos (inventados por mí, no del Excel).** Kit Esencial pasa de S/ 429 a **S/ 499** (suelto S/ 587, ahorro S/ 88, ≈15 %, similar al ahorro actual del Completo). El carrito pasa de S/ 507 a S/ 577. Brote S/ 129 sale de restar los demás precios al total suelto del Completo (S/ 994). Hay que confirmarlos.
- **Hallazgos que se contradicen:** Salim valora el Brote y la Almohada; la entrevista anterior pide fusionarlos o quitarlos. Se resolvió solo a nivel de kit (Nube dentro, Orbe fuera), sin fusionar hardware.
- **#15 («quitar las referencias») choca con #80 («referencias verificables»).** Se interpretó #15 como quitar la línea «Suelto» de la cabecera y #80 como explicar el cálculo debajo. Conviene confirmar qué quiso decir el entrevistado.
- **Afirmaciones de producto escritas como propuesta**, no como hechos verificados: carga magnética del Nido (compatibilidad por confirmar), registro de sonidos con el micrófono del teléfono, integración con reloj y Salud. Las tres quedan sujetas a viabilidad técnica y de privacidad (el propio Excel lo indica en #84). El texto no promete que el Brote grabe audio.

## No implementado

- #4, #18, #19, #21: **fusionar dispositivos** (medidor de ruido + Nido, Orbe + Almohada, Brote + Almohada) y «parametrizar productos». Requieren rediseño de producto y de los modelos 3D.
- #20: modelo 3D y precio del adaptador de techo para Alba.
- #26: modelo de suscripción. La web sigue diciendo «0 suscripciones»; requiere decisión de negocio.
- #82: integración real con otras marcas. Solo se aclara la compatibilidad actual.
- #22–#24 (diapositivas de la presentación) y #51 (pedir críticas más profundas): no aplican a estos tres prototipos.
