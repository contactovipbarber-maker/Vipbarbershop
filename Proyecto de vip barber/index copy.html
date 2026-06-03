<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vip Barber - Reservas y Tienda</title>
    <style>
        :root {
            --gold: #d4af37;
            --dark-bg: #121212;
            --card-bg: #1e1e1e;
            --text-color: #ffffff;
            --text-muted: #aaaaaa;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--dark-bg);
            color: var(--text-color);
            padding-bottom: 60px;
        }

        /* Header & Logo */
        header {
            text-align: center;
            padding: 20px;
            background-color: #0a0a0a;
            border-bottom: 2px solid var(--gold);
            position: relative;
        }

        .logo {
            max-width: 150px;
            border-radius: 50%;
            border: 2px solid var(--gold);
        }

        h1.brand-title {
            color: var(--gold);
            margin-top: 10px;
            font-size: 1.8rem;
            letter-spacing: 2px;
        }

        /* Botón Cerrar Sesión */
        .logout-btn {
            position: absolute;
            top: 20px;
            right: 20px;
            background-color: #cc2424;
            color: white;
            padding: 8px 15px;
            border-radius: 4px;
            font-size: 0.85rem;
            width: auto;
            text-transform: none;
        }
        .logout-btn:hover {
            background-color: #aa1e1e;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Auth Sections */
        .auth-container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 40px;
            min-height: 400px;
        }

        .card {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 8px;
            border: 1px solid #333;
            width: 100%;
            max-width: 450px;
        }

        .hidden {
            display: none !important;
        }

        h2 {
            color: var(--gold);
            margin-bottom: 20px;
            border-bottom: 1px solid var(--gold);
            padding-bottom: 5px;
        }

        .form-row {
            display: flex;
            gap: 10px;
        }

        .form-group {
            margin-bottom: 15px;
            flex: 1;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        .form-group input, .form-group select {
            width: 100%;
            padding: 10px;
            background-color: #2a2a2a;
            border: 1px solid #444;
            color: white;
            border-radius: 4px;
        }

        .form-group input:focus, .form-group select:focus {
            border-color: var(--gold);
            outline: none;
        }

        button {
            width: 100%;
            padding: 12px;
            background-color: var(--gold);
            color: black;
            border: none;
            font-weight: bold;
            border-radius: 4px;
            cursor: pointer;
            transition: background 0.3s, opacity 0.3s;
            text-transform: uppercase;
        }

        button:hover {
            background-color: #b3922e;
        }

        button:disabled {
            background-color: #555 !important;
            color: #888 !important;
            cursor: not-allowed;
        }

        .btn-secondary {
            background-color: #333;
            color: white;
            margin-top: 10px;
        }
        
        .btn-secondary:hover {
            background-color: #444;
        }

        .auth-toggle-text {
            text-align: center;
            margin-top: 15px;
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        .auth-toggle-text span {
            color: var(--gold);
            cursor: pointer;
            text-decoration: underline;
        }

        .forgot-password-link {
            display: block;
            text-align: right;
            margin-top: -10px;
            margin-bottom: 15px;
            font-size: 0.85rem;
            color: var(--gold);
            cursor: pointer;
            text-decoration: none;
        }

        /* Authenticator UI */
        .authenticator-box {
            background: #111;
            padding: 15px;
            border-radius: 6px;
            border: 1px dashed var(--gold);
            margin: 15px 0;
            text-align: center;
        }

        .secret-key {
            font-family: 'Courier New', Courier, monospace;
            font-size: 1.2rem;
            color: #ffcd38;
            letter-spacing: 2px;
            font-weight: bold;
            margin: 10px 0;
        }

        .min-amount-notice {
            color: #ff4d4d;
            font-size: 0.85rem;
            text-align: center;
            margin-bottom: 10px;
            display: none;
        }

        /* Main Content App */
        #main-app {
            display: grid;
            grid-template-columns: 1fr;
            gap: 40px;
        }

        @media (min-width: 768px) {
            #main-app {
                grid-template-columns: 1fr 2fr;
            }
        }

        /* Products Grid */
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
            gap: 20px;
        }

        .product-card {
            background-color: var(--card-bg);
            border: 1px solid #333;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        /* Contenedor de la Imagen del Producto */
        .product-image-wrapper {
            width: 100%;
            height: 180px;
            background-color: #111;
            border-radius: 6px;
            margin-bottom: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            border: 1px solid #222;
        }

        .product-img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
            transition: transform 0.3s ease;
        }

        .product-card:hover .product-img {
            transform: scale(1.05);
        }

        .product-title {
            font-size: 1.05rem;
            margin-bottom: 10px;
            height: 45px;
            overflow: hidden;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
        }

        .product-price {
            color: var(--gold);
            font-weight: bold;
            font-size: 1.2rem;
            margin-bottom: 15px;
        }

        /* Vertical Cart Sidebar */
        .cart-sidebar {
            position: fixed;
            top: 0;
            right: -400px;
            width: 100%;
            max-width: 380px;
            height: 100%;
            background-color: #1a1a1a;
            box-shadow: -5px 0 15px rgba(0,0,0,0.5);
            transition: right 0.3s ease;
            z-index: 1000;
            display: flex;
            flex-direction: column;
            border-left: 2px solid var(--gold);
        }

        .cart-sidebar.open {
            right: 0;
        }

        .cart-header {
            padding: 20px;
            background-color: #0a0a0a;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #333;
        }

        .close-cart {
            background: none;
            color: var(--gold);
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            width: auto;
        }

        .cart-items {
            flex: 1;
            overflow-y: auto;
            padding: 20px;
        }

        .cart-item {
            background-color: #252525;
            padding: 12px;
            border-radius: 6px;
            margin-bottom: 15px;
            border-left: 3px solid var(--gold);
        }

        .cart-item-details {
            margin-bottom: 8px;
        }

        .cart-item-controls {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 10px;
        }

        .cart-item-controls input {
            width: 60px;
            padding: 5px;
            background: #111;
            border: 1px solid #444;
            color: white;
            text-align: center;
        }

        .cart-footer {
            padding: 20px;
            background-color: #0a0a0a;
            border-top: 1px solid #333;
        }

        .cart-total {
            display: flex;
            justify-content: space-between;
            font-size: 1.3rem;
            font-weight: bold;
            margin-bottom: 15px;
            color: var(--gold);
        }

        /* Ventana de Métodos de Pago */
        .payment-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.8);
            z-index: 2000;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .payment-content {
            background-color: var(--card-bg);
            border: 2px solid var(--gold);
            border-radius: 8px;
            width: 90%;
            max-width: 650px;
            padding: 25px;
        }

        .payment-options-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
            gap: 15px;
            margin-top: 20px;
            margin-bottom: 20px;
        }

        .payment-btn-option {
            background-color: #2a2a2a;
            color: white;
            border: 1px solid #444;
            padding: 15px;
            font-size: 0.95rem;
        }

        .payment-btn-option:hover {
            border-color: var(--gold);
            background-color: #333;
        }

        .yape-container, .flow-container {
            background-color: #111;
            padding: 15px;
            border-radius: 6px;
            border: 1px solid #333;
            text-align: center;
            margin-top: 15px;
        }

        .qr-placeholder {
            max-width: 160px;
            margin: 10px auto;
            display: block;
            border: 4px solid white;
            border-radius: 4px;
        }

        /* Floating Cart Button */
        .floating-cart-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: var(--gold);
            color: black;
            padding: 15px 25px;
            border-radius: 30px;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 4px 10px rgba(0,0,0,0.4);
            z-index: 999;
            width: auto;
        }
    </style>
</head>
<body>

    <header>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRMLjaiuRQxfzIXkFxR3IAhKmU22ihzyOvJQ&s" alt="Logo Vip Barber" class="logo">
        <h1 class="brand-title">VIP BARBER</h1>
        <button id="logout-btn" class="logout-btn hidden" onclick="logout()">Cerrar Sesión</button>
    </header>

    <div class="container">

        <!-- SECCIÓN DE AUTENTICACIÓN -->
        <div class="auth-container" id="auth-section">
            
            <!-- Formulario Login (VISIBLE POR DEFECTO) -->
            <div class="card" id="login-card">
                <h2>Iniciar Sesión</h2>
                <form id="login-form">
                    <div class="form-group">
                        <label>Correo Electrónico</label>
                        <input type="email" id="login-email" required placeholder="correo@ejemplo.com">
                    </div>
                    <div class="form-group">
                        <label>Contraseña</label>
                        <input type="password" id="login-password" required placeholder="******">
                    </div>
                    <a class="forgot-password-link" onclick="showForgot()">¿Olvidaste tu contraseña?</a>
                    <button type="submit">Ingresar</button>
                    <p class="auth-toggle-text">¿No tienes cuenta? <span onclick="showRegister()">Registrarse</span></p>
                </form>
            </div>

            <!-- Formulario Registro Detallado (OCULTO POR DEFECTO) -->
            <div class="card hidden" id="register-card">
                <h2>Registrarse</h2>
                <form id="register-form">
                    <div class="form-row">
                        <div class="form-group">
                            <label>Nombres</label>
                            <input type="text" id="reg-name" required placeholder="Ej. Juan">
                        </div>
                        <div class="form-group">
                            <label>Apellidos</label>
                            <input type="text" id="reg-lastname" required placeholder="Ej. Pérez">
                        </div>
                    </div>
                    <div class="form-row">
                        <div class="form-group">
                            <label>DNI / CE</label>
                            <input type="text" id="reg-doc" required placeholder="Nº Documento">
                        </div>
                        <div class="form-group">
                            <label>Teléfono</label>
                            <input type="tel" id="reg-phone" required placeholder="987654321">
                        </div>
                    </div>
                    <div class="form-group">
                        <label>Correo Electrónico</label>
                        <input type="email" id="reg-email" required placeholder="correo@ejemplo.com">
                    </div>
                    <div class="form-group">
                        <label>Contraseña</label>
                        <input type="password" id="reg-password" required placeholder="******">
                    </div>
                    <button type="submit">Crear Cuenta</button>
                    <p class="auth-toggle-text">¿Ya tienes cuenta? <span onclick="showLogin()">Iniciar Sesión</span></p>
                </form>
            </div>

            <!-- Interfaz Recuperación con Autenticador -->
            <div class="card hidden" id="forgot-card">
                <h2>Recuperar Cuenta</h2>
                <div id="forgot-step-1">
                    <p style="font-size:0.9rem; margin-bottom:15px; color:var(--text-muted)">Introduce tu correo para vincular el autenticador.</p>
                    <div class="form-group">
                        <label>Correo Electrónico</label>
                        <input type="email" id="forgot-email" required placeholder="correo@ejemplo.com">
                    </div>
                    <button type="button" onclick="generateSecretKey()">Generar Llave Secreta</button>
                </div>

                <div id="forgot-step-2" class="hidden">
                    <p style="font-size:0.9rem; color:var(--text-muted)">¡Autenticador activado! Guarda tu clave:</p>
                    <div class="authenticator-box">
                        <small style="color:var(--gold)">SECRET KEY</small>
                        <div class="secret-key" id="display-secret-key">XXXX-XXXX-XXXX</div>
                        <small style="color: #4cd137">Token Temporal: <b id="display-token">123 456</b></small>
                    </div>
                    <div class="form-group">
                        <label>Ingresa el Token Temporal</label>
                        <input type="text" id="verify-token-input" placeholder="000 000">
                    </div>
                    <div class="form-group">
                        <label>Nueva Contraseña</label>
                        <input type="password" id="forgot-new-pass" placeholder="******">
                    </div>
                    <button type="button" onclick="verifyAndResetPassword()">Restablecer Contraseña</button>
                </div>
                <p class="auth-toggle-text"><span onclick="goBackInHistory()">Volver</span></p>
            </div>
        </div>

        <!-- SECCIÓN PRINCIPAL -->
        <div id="main-app" class="hidden">
            <!-- Panel de Reservas -->
            <div class="card">
                <h2>Reservar Cita</h2>
                <form id="booking-form">
                    <div class="form-group">
                        <label>Selecciona Servicio</label>
                        <select id="booking-service" required>
                            <option value="basic">Corte basic - S/ 20</option>
                            <option value="medium">Corte medium - S/ 30</option>
                            <option value="vip">Corte vip - S/ 45</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Fecha</label>
                        <input type="date" required id="booking-date">
                    </div>
                    <div class="form-group">
                        <label>Hora</label>
                        <select required>
                            <option value="10:00">10:00 AM</option>
                            <option value="11:00">11:00 AM</option>
                            <option value="12:00">12:00 PM</option>
                            <option value="14:00">02:00 PM</option>
                            <option value="15:00">03:00 PM</option>
                            <option value="16:00">04:00 PM</option>
                            <option value="17:00">05:00 PM</option>
                            <option value="18:00">06:00 PM</option>
                        </select>
                    </div>
                    <button type="submit">Agendar Cita</button>
                    <button type="button" class="btn-secondary" onclick="redirectToAgendaPro()">Domicilio</button>
                </form>
            </div>

            <!-- Tienda Vip Barber -->
            <div>
                <h2>Tienda Vip Barber</h2>
                <div class="products-grid" id="products-container"></div>
            </div>
        </div>
    </div>

    <!-- Carrito Lateral -->
    <div class="cart-sidebar" id="cart-sidebar">
        <div class="cart-header">
            <h3>Tu Carrito</h3>
            <button class="close-cart" onclick="toggleCart()">✕</button>
        </div>
        <div class="cart-items" id="cart-items-container"></div>
        <div class="cart-footer">
            <div class="cart-total">
                <span>Total:</span>
                <span id="cart-total-price">S/ 0.00</span>
            </div>
            <div class="min-amount-notice" id="min-notice">Monto mínimo de compra: S/ 50.00</div>
            <button id="checkout-btn" onclick="openPaymentWindow()" disabled>Confirmar Pago</button>
        </div>
    </div>

    <!-- VENTANA MODAL DE MÉTODOS DE PAGO -->
    <div class="payment-modal hidden" id="payment-modal">
        <div class="payment-content">
            <div style="display: flex; justify-content: space-between; align-items: center;">
                <h2 id="payment-title">Selecciona Método de Pago</h2>
                <button class="close-cart" style="font-size:1.2rem;" onclick="goBackInHistory()">Volver</button>
            </div>
            
            <div class="payment-options-grid" id="payment-menu-options">
                <button class="payment-btn-option" onclick="selectPaymentMethod('yape')">📱 YAPE</button>
                <button class="payment-btn-option" onclick="selectPaymentMethod('card')">💳 TARJETA DE CRÉDITO/DÉBITO</button>
                <button class="payment-btn-option" onclick="selectPaymentMethod('cash')">💵 PAGO EN EFECTIVO</button>
            </div>

            <!-- Interfaz de Yape -->
            <div id="yape-section" class="yape-container hidden">
                <h3>Escanea para pagar con Yape</h3>
                <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAgAAAQABAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBQNDAsLDBkSEw8UHRofHh0aHBwgJC4nICIsIxwcKDcpLDAxNDQ0Hyc5PTgyPC4zNDL/2wBDAQkJCQwLDBgNDRgyIRwhMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjL/wAARCAPoAt4DASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwDziiiivsD6kKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAoFFTWttNeTiC3XdKRkZNJtRV2Z1asKUHObskRHgUmcjI6V21l4SsokRrgtLJjJGcAGtmGxtrdQscSgDp3rlli4I+UxXF2GpS5KacmeYZyMjp60Yr0y502zvF2zwq49uDWDqfhOPy2ewBEg/hZuMU44qEtDTBcWYWtJQqJps5GinSI0TlHXaynBFNrpTT2PqYyUlzRd0FFFFMoKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigEKASwC/eJwPrXoWiaVHp1ohAzK65Zj1Ge1cfoNqLrVokccD5vyr0P7qHA6DpXBi5u/Kj4Pi/Hzi1h4O19xfftQCCM5GK5nVJ573X101ZjBGpxuU/eBGabdWd3ojQ3EFxLNGWwysc1zKl3PnI5QvZx552k9TqKOKZBJ5sKSYwWGawb2Z9T1mOygdljg+d2U9faojB3Zw0MHKpKcb6R6jfE2kieH7ZEP3q53AdMVxQORmvVnRZIjGRkOpH5jFeWzJ5c8if3XZfwBx/QV6GEnfQ+94Ux861OdCbvy7MZRRRXWfYPcKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigL21Nvwu4XW1zxlDiu86N+OK8vs7g2t3FMpxtIz9M16bHKssIkQggjcMd687GQfNdH5xxjh5QxEa3Rox721sdVumjjuDFeQHlkHP3RVGS51DRpdl6PtNoSAHbtUmqWF5Z6odRsBuLnLoB1qC5bVNaWO2ezaGPOWZqUbWROGjDkipSThbq9V6G1qGpxWulideRKMRgetQeH7E29qZ5QfPm5Yn0qvJpU099Z2zgi2tl3biOGNdCBhdq44FZVHGMbJnl4yrTw9H2NF35nqKMbgT06/TFeWXLB7udh0aRiPpmvRNWvo7DT5JW4ZlIUe/SvN+3vXVgotXZ9Hwbh5wjOrLqJRRRXafdPcKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAIyMetdh4Ru5pYpoHOVQjbjtXHjrXU+FbmCzsrqWWRVO4cd6wxEeaFjwuIaLrYJxirs67J55INLk46/ka4u98W3LSkWYRYgerr1pkfjC+CgNDCT61xLC1LaHw1PhfMJU1KPXoduc46nA6VXu7yCygMk0irjsTya46bxdqDjEaQx+45rHub24vX3XEpc5zz0FVHCO95Hdg+EK8pp4h2Ra1fVZNUuNx+WIH5VrO6UUV6EYqCsfoOGoU6FNU4LYKKMUd8VVjcKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACik3DOM8+nf8qXr70KzEmnsHejkg46HrivRPCfwsuNe09b69uJLWJuUQDkj1rlbnw9cN4sudD0zNxIkzRoSew5yf1rCOJpyk49jH21ObcexjYGP5Cm5GQMjPpXu1h8GtCislF69xNOVG5hKVAPccVs6P8ADnRdHtbmHYbhJgf9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OlLRRXq6dD0gooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACprW6ms5lnt5WjkBGCpxn61D0GTwMZ5rtfBvw6v/FDGaZpLSxAyJQuS/0rOrUhCN57GdWcIQvIqaK+qeLvEtna3dw8uHDkE8YB9K+gtcaey8PXBtIjJKkW1EHftWV4Y8AaP4VlM9osj3BXaZZJCf06V0V7qFnp8Pm3dwkUYHVzXz+IrqpUTprRHi4isqk1yI+e4vhn4o1GV5jbRx+Y5bLvzyfpXQWHwVu5Bm/vBGTj/Vc/zrvrv4l+FrMEf2jG7DoEGa5S9+N1vGxW00t5eThjIADXWq+LmrRWh0KriJL3VoXrb4L6JEB9oubmX2zj+VdFonw/0LQLpLmzgImXozEk5ry67+M+vSki3s7W3XPXlj+tanhT4tTm4uP+EjuYgpGYvLjx/Ks50MW4+89CZ0cTa7Z63e2dhcmN7yONjHkoXxxUEl5o9mmXltUA9CvFfOvivxZea5rlxcQ3U0VsxxGiuQMetc8Z5W6yyH6saqllsmk3KxUMDJpOUj6RuviJ4Ws5Ckl+m4dlXNZs/wAX/DUQOxpn9MIa+fTzz39aM5PSulZZT6u5usBDqz1/VfjKjwsllZbt2QC/FeSXNw91dTXD4DSuXbHqaiorro4enS+BHTToQp/CFFFFb69TYKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACj68D1orZ8LaIfEHiO1sDkxSHMpHZamc+SLkTOXJFyOz+HPw6fV5I9W1VHjsxtkgTP+uzn7w9Bx+deneIfFmjeDNPSKRo432kQW6Dk4HoKk8Q61aeDPDLTDywYYtsERONxGOBXiGh2uo+OvGazTl5AZPMlJ5EcZOcCvFUXiZOrUfuo8mzrt1J/Cj3jwtq91rWgW+o3kCQNMN/lqcgCvFPijrral4slgguGNrCqrtDcFhnP9K9l8R6raeFvDEkhCoiJ5cajjnHAr5hlleaaSWUlndizEnvVZdRUpup0LwVJSm59BlFFFe1p2PVDn1pckdKSigN9wAGO+aKKKAYUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFeq/BS3hk1G/ncDzY1UJn3FeVV0Xg3xK/hfW0uyGa3PEqr3rnxUJTpNR3McRBzptI9H+LWlaxreq6Va2NnJLCgkbcBlQflxn9a6jwJ4Rt/CWkFpSv2qVAZ3Pap7P4geH7mxFybxE4zsY/NXnfjn4ojUbZtO0XeqH5ZpCOo9q8iMa1SKopWR5UY1ZxVK1kij8VvFketaiul2xJt7V8s4OQ5xxXnGKUH0or2qNKNKCgj1qNNU4KKCiiitTUKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKAA8446UdqKKNACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKLgFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRR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" alt="QR Yape" class="qr-placeholder">
                <p style="font-size:0.9rem; margin-bottom:15px; color:var(--gold);">Escanea el código QR desde tu app Yape y realiza el abono.</p>
                <div class="form-group" style="text-align: left; max-width: 400px; margin: 0 auto 15px;">
                    <label>Sube tu comprobante de pago aquí:</label>
                    <input type="file" id="receipt-file" accept="image/*" onchange="validateReceipt()">
                </div>
                <button id="whatsapp-btn" onclick="sendReceiptToWhatsApp()" disabled>Enviar comprobante a WhatsApp</button>
            </div>

            <!-- Interfaz de Tarjetas / Efectivo -->
            <div id="flow-section" class="flow-container hidden">
                <h3 id="flow-subtitle">Procesar pago seguro</h3>
                <p style="font-size:0.95rem; margin:15px 0; color:var(--text-muted);">Haz clic en el siguiente botón para conectarte de forma segura con los servidores de pago oficiales.</p>
                <button style="max-width:300px; margin:0 auto; display:block;" onclick="redirectToFlowExternal()">PAGAR AHORA</button>
            </div>
        </div>
    </div>

    <button class="floating-cart-btn hidden" id="floating-cart" onclick="toggleCart()">
        🛒 Carrito (<span id="cart-count">0</span>)
    </button>

    <script>
        const products = [
            { id: 1, name: "Laca Spray Gold Bandido 400 ml", price: 20, options: false, image: "https://media.falabella.com/falabellaPE/143455483_01/w=1200,h=1200,fit=pad" },
            { id: 2, name: "Polvo Texturizador Bandido Matte", price: 30, options: false, image: "https://http2.mlstatic.com/D_NQ_NP_2X_875420-MLA92308045378_092025-F.webp" },
            { id: 3, name: "After Shave Bandido 350 ml", price: 28, options: true, image: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJ4ahuZRwDiPZAmykZPDftQbPaqSzrYNcLSA&s" },
            { id: 4, name: "Bandido Shaving Gel 1000ml", price: 30, options: true, image: "https://images-eu.ssl-images-amazon.com/images/I/511DfGLpKiL._AC_UL495_SR435,495_.jpg" },
            { id: 5, name: "Cera Bandido", price: 20, options: true, image: "https://media.falabella.com/falabellaPE/129020827_01/w=1200,h=1200,fit=pad" },
            { id: 6, name: "Cera Telaraña Bandido", price: 30, options: false, image: "https://plazavea.vteximg.com.br/arquivos/ids/32234735-465-465/imageUrl_1.jpg" },
            { id: 7, name: "Cera Level Up", price: 23, options: false, image: "https://media.falabella.com/falabellaPE/137328029_01/w=1200,h=1200,fit=pad" }
        ];

        let cart = [];
        let generatedToken = ""; 

        const registerCard = document.getElementById('register-card');
        const loginCard = document.getElementById('login-card');
        const forgotCard = document.getElementById('forgot-card');
        const authSection = document.getElementById('auth-section');
        const mainApp = document.getElementById('main-app');
        const floatingCart = document.getElementById('floating-cart');
        const logoutBtn = document.getElementById('logout-btn');

        window.addEventListener('load', () => {
            history.replaceState({page: 'login'}, "Login");
        });

        function goBackInHistory() {
            history.back(); 
        }

        window.addEventListener('popstate', function(event) {
            if (event.state) {
                if (event.state.page === 'payment') {
                    document.getElementById('payment-modal').classList.remove('hidden');
                    document.getElementById('payment-menu-options').classList.remove('hidden');
                    document.getElementById('yape-section').classList.add('hidden');
                    document.getElementById('flow-section').classList.add('hidden');
                    document.getElementById('payment-title').innerText = "Selecciona Método de Pago";
                } 
                else if (event.state.page === 'app') {
                    document.getElementById('payment-modal').classList.add('hidden');
                    authSection.classList.add('hidden'); 
                    mainApp.classList.remove('hidden'); 
                    floatingCart.classList.remove('hidden');
                    logoutBtn.classList.remove('hidden');
                } 
                else if (event.state.page === 'login') {
                    closeAllModals();
                    authSection.classList.remove('hidden'); mainApp.classList.add('hidden'); floatingCart.classList.add('hidden'); logoutBtn.classList.add('hidden');
                    registerCard.classList.add('hidden'); forgotCard.classList.add('hidden'); loginCard.classList.remove('hidden');
                } 
                else if (event.state.page === 'register') {
                    closeAllModals();
                    authSection.classList.remove('hidden'); mainApp.classList.add('hidden'); floatingCart.classList.add('hidden'); logoutBtn.classList.add('hidden');
                    loginCard.classList.add('hidden'); forgotCard.classList.add('hidden'); registerCard.classList.remove('hidden');
                } 
                else if (event.state.page === 'forgot') {
                    closeAllModals();
                    authSection.classList.remove('hidden'); mainApp.classList.add('hidden'); floatingCart.classList.add('hidden'); logoutBtn.classList.add('hidden');
                    loginCard.classList.add('hidden'); registerCard.classList.add('hidden'); forgotCard.classList.remove('hidden');
                }
            }
        });

        function closeAllModals() {
            document.getElementById('payment-modal').classList.add('hidden');
        }

        function showLogin() {
            history.pushState({page: 'login'}, "Login");
            registerCard.classList.add('hidden'); forgotCard.classList.add('hidden'); loginCard.classList.remove('hidden');
        }
        function showRegister() {
            history.pushState({page: 'register'}, "Register");
            loginCard.classList.add('hidden'); forgotCard.classList.add('hidden'); registerCard.classList.remove('hidden');
        }
        function showForgot() {
            history.pushState({page: 'forgot'}, "Forgot");
            loginCard.classList.add('hidden'); registerCard.classList.add('hidden'); forgotCard.classList.remove('hidden');
            document.getElementById('forgot-step-1').classList.remove('hidden'); document.getElementById('forgot-step-2').classList.add('hidden');
        }

        function logout() {
            cart = [];
            updateCartUI();
            if(document.getElementById('cart-sidebar').classList.contains('open')) { toggleCart(); }
            closeAllModals();
            mainApp.classList.add('hidden');
            floatingCart.classList.add('hidden');
            logoutBtn.classList.add('hidden');
            authSection.classList.remove('hidden');
            showLogin();
        }

        // --- CORRECCIÓN AQUÍ: PROCESO DE REGISTRO GUARDANDO DATOS ---
        document.getElementById('register-form').addEventListener('submit', (e) => {
            e.preventDefault();
            
            const emailInput = document.getElementById('reg-email').value.trim();
            const passwordInput = document.getElementById('reg-password').value;

            // Guardamos las credenciales directamente en el navegador del usuario
            localStorage.setItem('registeredEmail', emailInput);
            localStorage.setItem('registeredPassword', passwordInput);

            alert('¡Registro exitoso! Tus credenciales se han guardado. Ahora puedes iniciar sesión.');
            
            // Auto-completamos los campos del Login para facilitarle el ingreso
            document.getElementById('login-email').value = emailInput;
            document.getElementById('login-password').value = passwordInput;
            showLogin();
        });

        // --- CORRECCIÓN AQUÍ: COMPROBACIÓN REAL DE CREDENCIALES ---
        document.getElementById('login-form').addEventListener('submit', (e) => {
            e.preventDefault();
            
            const emailInput = document.getElementById('login-email').value.trim();
            const passwordInput = document.getElementById('login-password').value;

            // Extraemos los datos que fueron guardados previamente en el Registro
            const savedEmail = localStorage.getItem('registeredEmail');
            const savedPassword = localStorage.getItem('registeredPassword');

            // Caso 1: El usuario no se ha registrado aún
            if (!savedEmail || !savedPassword) {
                alert("No se encontró ninguna cuenta registrada en este dispositivo. Por favor, haz clic en 'Registrarse'.");
                return;
            }

            // Caso 2: Comprobación estricta de credenciales
            if (emailInput === savedEmail && passwordInput === savedPassword) {
                // Si coinciden los datos, damos acceso a la tienda
                authSection.classList.add('hidden'); 
                mainApp.classList.remove('hidden'); 
                floatingCart.classList.remove('hidden');
                logoutBtn.classList.remove('hidden'); 
                renderProducts();
                document.getElementById('booking-date').min = new Date().toISOString().split('T')[0];
                history.pushState({page: 'app'}, "Dashboard VIP");
            } else {
                // Si falla el correo o la contraseña
                alert("Correo electrónico o contraseña incorrectos. Por favor, verifica tus datos.");
            }
        });

        function generateSecretKey() {
            const email = document.getElementById('forgot-email').value;
            if(!email) { alert("Por favor introduce tu correo."); return; }
            const characters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ234567';
            let secretKey = '';
            for (let i = 0; i < 16; i++) {
                if(i > 0 && i % 4 === 0) secretKey += '-';
                secretKey += characters.charAt(Math.floor(Math.random() * characters.length));
            }
            generatedToken = Math.floor(100000 + Math.random() * 900000).toString();
            document.getElementById('display-secret-key').innerText = secretKey;
            document.getElementById('display-token').innerText = `${generatedToken.substring(0,3)} ${generatedToken.substring(3,6)}`;
            document.getElementById('forgot-step-1').classList.add('hidden');
            document.getElementById('forgot-step-2').classList.remove('hidden');
        }

        function verifyAndResetPassword() {
            const userInput = document.getElementById('verify-token-input').value.replace(/\s+/g, '');
            const newPass = document.getElementById('forgot-new-pass').value;
            if(!newPass) { alert("Ingresa tu nueva contraseña."); return; }
            if(userInput === generatedToken) {
                // Actualiza también en localStorage para no perder el acceso en el Login corregido
                localStorage.setItem('registeredPassword', newPass);
                alert("Llave verificado con éxito. Contraseña actualizada.");
                document.getElementById('login-password').value = newPass;
                showLogin();
            } else { alert("Token incorrecto."); }
        }

        function renderProducts() {
            const container = document.getElementById('products-container');
            container.innerHTML = '';
            products.forEach(product => {
                let optionsHtml = '';
                if(product.options) {
                    optionsHtml = `
                        <div class="form-group" style="margin-top:5px; text-align:left;">
                            <label style="font-size:0.8rem; margin-bottom: 2px;">Color:</label>
                            <select id="color-${product.id}" style="padding: 5px; font-size: 0.85rem;">
                                <option value="Rojo">Rojo</option><option value="Azul">Azul</option><option value="Verde">Verde</option><option value="Marrón">Marrón</option>
                            </select>
                        </div>
                    `;
                } else {
                    optionsHtml = `<div style="height: 48px;"></div>`;
                }
                container.innerHTML += `
                    <div class="product-card">
                        <div>
                            <div class="product-image-wrapper">
                                <img src="${product.image}" alt="${product.name}" class="product-img" onerror="this.src='https://placehold.co/400x400/1a1a1a/ffffff?text=Producto'">
                            </div>
                            <div class="product-title">${product.name}</div>
                            <div class="product-price">S/ ${product.price.toFixed(2)}</div>
                            ${optionsHtml}
                        </div>
                        <button onclick="addToCart(${product.id})" style="margin-top: 10px;">Añadir al carrito</button>
                    </div>
                `;
            });
        }

        function toggleCart() { document.getElementById('cart-sidebar').classList.toggle('open'); }

        function addToCart(productId) {
            const product = products.find(p => p.id === productId);
            let selectedColor = product.options ? document.getElementById(`color-${productId}`).value : "Único";
            const existingItem = cart.find(item => item.id === productId && item.color === selectedColor);
            if(existingItem) { existingItem.quantity++; } else {
                cart.push({ id: product.id, name: product.name, price: product.price, color: selectedColor, quantity: 1 });
            }
            updateCartUI();
            document.getElementById('cart-sidebar').classList.add('open');
        }

        function updateCartUI() {
            const container = document.getElementById('cart-items-container');
            container.innerHTML = ''; let total = 0; let totalItems = 0;
            cart.forEach((item, index) => {
                total += item.price * item.quantity; totalItems += item.quantity;
                container.innerHTML += `
                    <div class="cart-item">
                        <div class="cart-item-details">
                            <strong>${item.name}</strong><br><small style="color:var(--gold)">Color: ${item.color}</small><br><span>Precio: S/ ${item.price}</span>
                        </div>
                        <div class="cart-item-controls">
                            <input type="number" min="1" value="${item.quantity}" onchange="changeQuantity(${index}, this.value)">
                            <button class="btn-remove" onclick="removeItem(${index})">Eliminar</button>
                        </div>
                    </div>
                `;
            });
            document.getElementById('cart-total-price').innerText = `S/ ${total.toFixed(2)}`;
            document.getElementById('cart-count').innerText = totalItems;
            
            const checkoutBtn = document.getElementById('checkout-btn');
            const minNotice = document.getElementById('min-notice');
            if (total >= 50) { checkoutBtn.disabled = false; minNotice.style.display = 'none'; } 
            else { checkoutBtn.disabled = true; minNotice.style.display = cart.length > 0 ? 'block' : 'none'; }
        }

        function changeQuantity(index, val) {
            let qty = parseInt(val); if(qty < 1 || isNaN(qty)) qty = 1;
            cart[index].quantity = qty; updateCartUI();
        }
        function removeItem(index) { cart.splice(index, 1); updateCartUI(); }

        function openPaymentWindow() {
            history.pushState({page: 'payment'}, "Metodo de Pago");
            document.getElementById('payment-modal').classList.remove('hidden');
            document.getElementById('payment-menu-options').classList.remove('hidden');
            document.getElementById('yape-section').classList.add('hidden');
            document.getElementById('flow-section').classList.add('hidden');
            document.getElementById('payment-title').innerText = "Selecciona Método de Pago";
        }

        function selectPaymentMethod(method) {
            history.pushState({page: 'payment_detail', method: method}, "Procesando Pago");
            document.getElementById('payment-menu-options').classList.add('hidden');

            if(method === 'yape') {
                document.getElementById('payment-title').innerText = "Pago con Yape";
                document.getElementById('yape-section').classList.remove('hidden');
            } 
            else if(method === 'card') {
                document.getElementById('payment-title').innerText = "Pago con Tarjeta";
                document.getElementById('flow-subtitle').innerText = "Pagar con Tarjeta de Crédito / Débito";
                document.getElementById('flow-section').classList.remove('hidden');
            } 
            else if(method === 'cash') {
                document.getElementById('payment-title').innerText = "Pago en Efectivo";
                document.getElementById('flow-subtitle').innerText = "Generar código para Pago en Efectivo";
                document.getElementById('flow-section').classList.remove('hidden');
            }
        }

        function validateReceipt() {
            const fileInput = document.getElementById('receipt-file');
            document.getElementById('whatsapp-btn').disabled = fileInput.files.length === 0;
        }

        function sendReceiptToWhatsApp() {
            window.location.href = "https://wa.me/message/HSE2KYPTYVRNF1";
        }

        function redirectToFlowExternal() {
            window.location.href = "https://www.flow.cl/btn.php?token=y33383426df8d6f796fd04a1d6867f7427d2cd34";
        }

        function redirectToAgendaPro() { window.location.href = "https://vipbarbershop.site.agendapro.com/pe"; }
        document.getElementById('booking-form').addEventListener('submit', (e) => { e.preventDefault(); redirectToAgendaPro(); });
    </script>
</body>
</html>