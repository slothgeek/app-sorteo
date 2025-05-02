# Sorteo de Rifas

Una aplicación web moderna y segura para realizar sorteos de manera justa y transparente, desarrollada con Astro y Tailwind CSS.

## 🎯 Características

- **Múltiples formas de entrada**: Ingresa correos electrónicos directamente o sube un archivo
- **Validación de correos**: Verificación automática de formatos de correo válidos
- **Protección visual**: Opción para ocultar el correo del ganador con efecto de blur
- **Animaciones atractivas**: Interfaz dinámica con mensajes y barra de progreso
- **Efectos visuales**: Confeti al anunciar al ganador
- **Funcionalidad de copia**: Botón para copiar el correo del ganador al portapapeles
- **Diseño responsivo**: Se adapta a diferentes tamaños de pantalla

## 🚀 Instrucciones de Uso

### 1. Ingreso de Participantes

Puedes cargar los correos de los participantes de dos formas:

- **Directamente**: Ingresa los correos uno por línea en el área de texto
- **Archivo**: Sube un archivo de texto (.txt) o CSV con los correos

### 2. Configuración del Sorteo

- Marca la casilla "Proteger visualmente el correo del ganador" si deseas que el resultado se muestre con efecto de blur
- Haz clic en "Realizar Sorteo" para comenzar

### 3. Durante el Sorteo

- Observa los mensajes animados que indican el progreso
- La barra de progreso muestra el avance del sorteo
- Los puntos de carga indican que el proceso está activo

### 4. Resultado

- Se muestra el correo del ganador con animación
- Si la protección visual está activada, puedes usar el botón "Mostrar/Ocultar"
- Usa el botón "Copiar correo" para copiar el resultado al portapapeles
- El botón "Realizar otro sorteo" reinicia la aplicación

## 🔒 Metodología del Sorteo

El sorteo se realiza utilizando un algoritmo criptográficamente seguro:

1. **Validación**: Se verifica que todos los correos sean válidos
2. **Mezcla**: Se aplica el algoritmo Fisher-Yates para mezclar aleatoriamente la lista
3. **Selección**: Se genera un número aleatorio seguro usando `crypto.getRandomValues`
4. **Resultado**: Se selecciona el ganador de manera imparcial

## 🛠️ Tecnologías Utilizadas

- **Astro**: Framework moderno para construir sitios web rápidos
- **Tailwind CSS**: Framework de utilidades CSS para diseño responsivo
- **TypeScript**: Tipado estático para mayor seguridad en el código
- **Canvas Confetti**: Biblioteca para efectos visuales de confeti

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone [URL_DEL_REPOSITORIO]
```

2. Instala las dependencias:
```bash
npm install
```

3. Inicia el servidor de desarrollo:
```bash
npm run dev
```

## 🌟 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir los cambios propuestos o envía un pull request.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.
