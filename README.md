# Welcome to AFJP Cripto

## Project info

**URL**: https://tmar4-xaaaa-aaaad-abn5q-cai.icp0.io/

## How can I create an account?

There isn't any button to do so because we are yet to develop the backend.


The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
# Step 5: Create dfx.json in project folder and add the following:

{
  "canisters": {
    "frontend": {
      "source": ["dist"],
      "type": "assets"
    }
  },
  "defaults": {
    "build": {
      "args": "",
      "packtool": ""
    }
  },
  "output_env_file": ".env",
  "version": 1
}
# Step 6: Save your project.

# Step 7: Run this command:
dfx start --clean

# Step 8: Run this command to deploy locally:
dfx deploy


**Edit a file in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

# AFJP Cripto - Sistema de jubilación basado en criptomonedas

## Introducción
AFJP Cripto presenta un modelo innovador de sistema de jubilación que utiliza tecnología blockchain, integrando tokens de ahorro jubilatorio, inversiones en bolsa y oportunidades en bienes raíces tokenizados. Cada aporte genera **Tokens AFJP**, que representan los ahorros para la jubilación, los cuales pueden intercambiarse en un submercado dedicado. La plataforma ofrece beneficios exclusivos para afiliados, como acceso a propiedades tokenizadas (RWA), opciones de jubilación anticipada y un sistema de jubilación seguro, flexible y rentable gestionado a través de una billetera virtual.

## Características principales
- **Ahorro jubilatorio**: Obtén **tokens AFJP** mediante aportes, los cuales permanecen bloqueados por 5 años (vesting). Posteriormente, pueden venderse, intercambiarse por **tokens LADRILLO** (bienes raíces) o **JUVENTUD** (alquileres), o mantenerse para la jubilación.
- **Bienes raíces tokenizados**: Compra fracciones de propiedades con **tokens LADRILLO** y obtén ingresos proporcionales por alquileres. Alquila propiedades con **tokens JUVENTUD**.
- **Mercado**: Compra, vende o intercambia tokens (AFJP, LADRILLO, JUVENTUD) con dinero fiat, criptomonedas u otros tokens.
- **Beneficios exclusivos**: Accede a beneficios inmobiliarios, farmacéuticos y turísticos para afiliados activos.
- **Herencia de Tokens**: Designa billeteras beneficiarias para la herencia de tokens en caso de fallecimiento del usuario.

## Primeros pasos

### Crear tu billetera
1. Instala la extensión o aplicación de **Lace Wallet**.
2. Haz clic en **"Conectar Lace Wallet para acceder a AFJP Cripto"** en la plataforma.
3. Selecciona **"Crear nueva billetera"**.
4. Ingresa tus datos personales y haz clic en **"Completar registro AFJP Cripto"**.
5. Guarda de forma segura tu frase mnemotécnica y contraseña.

### Iniciar sesión
1. Haz clic en **"Conectar Lace Wallet para acceder a AFJP Cripto"**.
2. Ingresa tu contraseña.
   - Si la olvidaste, haz clic en **"Restablecer billetera"** e ingresa tu frase mnemotécnica.
   - Para acceder desde un nuevo dispositivo, selecciona **"Importar billetera"** e ingresa tu frase mnemotécnica.

## Funcionalidades de la plataforma

### Panel Principal
- **Selección de idioma**: Elige tu idioma preferido desde el menú superior derecho, junto al botón **"Cerrar sesión"**.
- **Resumen de Tokens**: Muestra tus **Tokens AFJP**, su valor actual, ganancias obtenidas y el precio por token.
- **Estadísticas de la plataforma**: Visualiza estadísticas generales de la plataforma y sus usuarios, seguidas de estadísticas totales de todos los tokens de la plataforma.
- **Botones de acción**:
  1. **Aportar Tokens AFJP**: Elige entre el aporte mensual mínimo o una cantidad personalizada. Los tokens quedan bloqueados por 5 años (vesting), luego pueden venderse, intercambiarse por **tokens LADRILLO** o **JUVENTUD**, o mantenerse.
  2. **Comprar Tokens LADRILLO**: Usa **tokens AFJP** desbloqueados o dinero fiat para adquirir **tokens LADRILLO** de otros usuarios o de la plataforma. También permite vender **tokens AFJP** o **LADRILLO** a otros usuarios.
  3. **Beneficios**: Navega a la sección de Beneficios para acceder a ventajas exclusivas.
- **Transacciones recientes**: Consulta el historial de transacciones de tu billetera.
- **Noticias de la plataforma**: Lee actualizaciones y artículos haciendo clic en las noticias.

### Aportes
- **Estadísticas del usuario**: Visualiza estadísticas personalizadas de tu billetera y aportes.
- **Historial de Tokens AFJP**: Revisa el historial de **Tokens AFJP** comprados.
- **Formulario de compra**: Adquiere **Tokens AFJP** con dinero fiat.

### Mercado
- **Estadísticas en tiempo real**: Monitorea el rendimiento de los **tokens AFJP**.
- **Comprar Tokens**: Adquiere **tokens AFJP** o **LADRILLO** con moneda local, dólares o criptomonedas.
- **Vender Tokens**: Intercambia **tokens AFJP** por dinero fiat (dólares, pesos, etc.).
- **Intercambio de Tokens**: Cambia **tokens AFJP** por **tokens LADRILLO** o **JUVENTUD**.
- **Crédito**: Solicita un préstamo bloqueando tokens como garantía y selecciona el plazo de pago.

### Inmuebles
- **Beneficios para afiliados**: Explora los beneficios inmobiliarios actuales para afiliados.
- **Listado de propiedades**: Consulta propiedades tokenizadas (RWA) disponibles para compra o alquiler, con detalles específicos.
- **Compra/alquiler**: Compra fracciones de propiedades con **tokens LADRILLO** o alquila con **tokens JUVENTUD**.
- **Suscripción a newsletter**: Regístrate para recibir actualizaciones sobre nuevas propiedades y beneficios.

### Turismo (Solo afiliados)
- **Reserva de propiedades**: Selecciona fechas en el calendario y haz clic en **"Reservar Ahora"** para reservar una propiedad.

### Beneficios
- **Ventajas para afiliados**: Accede a beneficios inmobiliarios, farmacéuticos y médicos para afiliados activos.
- **Herencia de tokens**: Designa billeteras beneficiarias para la herencia de tokens.
- **Enlace al mercado**: Navega a la sección **Mercado** para transacciones de tokens.
- **Pagos**: Paga alquileres, servicios médicos o farmacéuticos con **tokens JUVENTUD** mediante código QR o dirección pública.
- **Calculadora de descuentos**: Calcula descuentos en medicamentos ingresando su precio.
- **Información de beneficiarios**: Visualiza o modifica los detalles de los beneficiarios de tokens.

## Acerca de
Este proyecto es un MVP desarrollado para el **ICP - WCHL25 - National Round**, que presenta un sistema de jubilación descentralizado basado en tecnología blockchain.
