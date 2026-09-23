<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PanaXtreaming - Plataforma de Gestión y Entretenimiento</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background-color: #0b0f19;
            color: #ffffff;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #111827;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #374151;
            border-radius: 3px;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col">

    <!-- BARRA SUPERIOR -->
    <header class="bg-gray-900 border-b border-gray-800 px-4 py-3 flex justify-between items-center shadow-lg z-20">
        <div class="flex items-center space-x-3">
            <span class="text-red-600 font-black text-xl tracking-wider cursor-pointer" onclick="irAlInicio()">PANAXTREAMING</span>
            <span class="hidden md:inline text-xs bg-red-950 text-red-400 border border-red-800 px-2 py-0.5 rounded font-semibold">ST3TLLA TV &amp; F1UJO TV</span>
        </div>
        <div class="flex items-center space-x-4">
            <div id="topWalletDisplay" class="hidden items-center bg-gray-800 border border-gray-700 px-3 py-1.5 rounded-lg text-sm">
                <span class="text-green-400 font-bold mr-2" id="topSaldoUsd">Saldo: $0.00</span>
            </div>
            <button id="btnSalirSesion" class="hidden bg-red-600 hover:bg-red-700 text-white px-3 py-1.5 rounded text-xs font-bold transition" onclick="cerrarSesion()">Salir</button>
            <div id="topPublicBtns" class="flex space-x-2">
                <button class="bg-gray-800 hover:bg-gray-700 text-white px-3 py-1.5 rounded text-xs font-bold transition border border-gray-700" onclick="mostrarPantalla('registerScreen')">Registrarse</button>
                <button class="bg-red-600 hover:bg-red-700 text-white px-3 py-1.5 rounded text-xs font-bold transition" onclick="mostrarPantalla('loginScreen')">Iniciar Sesión</button>
            </div>
        </div>
    </header>

    <!-- CONTENEDOR GENERAL -->
    <main class="flex-1 flex flex-col">

        <!-- 1. INICIO PÚBLICO -->
        <div id="homeHero" class="flex-1 flex flex-col items-center justify-center text-center p-6 max-w-4xl mx-auto my-auto">
            <h1 class="text-3xl md:text-5xl font-black uppercase tracking-tight mb-4 text-white drop-shadow-md">
                Películas, series ilimitadas y TV en vivo, en un solo lugar
            </h1>
            <p class="text-gray-400 text-sm md:text-base mb-8 max-w-xl">
                Disfruta de la mejor plataforma de entretenimiento con soporte garantizado, perfiles privados y recargas al instante.
            </p>
            <div class="flex flex-col sm:flex-row gap-3 w-full max-w-md justify-center">
                <input type="email" id="heroEmail" placeholder="Correo electrónico para empezar" class="px-4 py-3 bg-gray-900 border border-gray-700 rounded text-sm text-white focus:outline-none focus:border-red-600 flex-1">
                <button onclick="empezarRegistroHero()" class="bg-red-600 hover:bg-red-700 text-white px-6 py-3 rounded font-black text-sm uppercase tracking-wider transition shadow-lg">Comenzar &gt;</button>
            </div>
            <div class="mt-6">
                <a href="javascript:void(0);" onclick="mostrarPantalla('adminLoginScreen')" class="text-gray-400 hover:text-white text-xs underline font-bold">🔐 Acceso Panel Administrador</a>
            </div>
        </div>

        <!-- 2. LOGIN DE ADMINISTRADOR -->
        <div id="adminLoginScreen" class="hidden flex-1 flex items-center justify-center p-4">
            <div class="bg-gray-900/95 border border-red-900/50 p-8 rounded-xl shadow-2xl max-w-md w-full text-center">
                <div class="text-3xl mb-2">🛡️</div>
                <h2 class="text-xl font-bold uppercase mb-2 text-white">Acceso de Administrador</h2>
                <p class="text-xs text-gray-400 mb-6">Ingresa tus credenciales de control</p>
                
                <input type="text" id="adminUser" placeholder="Usuario (admin)" class="w-full bg-black border border-gray-700 p-3 rounded text-sm mb-4 text-white focus:border-red-600 outline-none">
                <input type="password" id="adminPass" placeholder="Contraseña (adming1234)" class="w-full bg-black border border-gray-700 p-3 rounded text-sm mb-6 text-white focus:border-red-600 outline-none">
                
                <button onclick="verificarLoginAdmin()" class="w-full bg-red-600 hover:bg-red-700 text-white p-3 rounded font-black text-sm uppercase transition shadow-lg mb-3">Ingresar como Admin</button>
                <button onclick="mostrarPantalla('homeHero')" class="text-xs text-gray-500 hover:text-gray-300 underline">Volver al inicio</button>
            </div>
        </div>

        <!-- 3. PANTALLA DE REGISTRO CLIENTE -->
        <div id="registerScreen" class="hidden flex-1 flex items-center justify-center p-4">
            <div class="bg-gray-900/95 border border-red-900/50 p-8 rounded-xl shadow-2xl max-w-md w-full text-center">
                <h2 class="text-xl font-bold uppercase mb-2 text-white">Crear Cuenta</h2>
                <input type="email" id="reg-email" placeholder="Correo electrónico" class="w-full bg-black border border-gray-700 p-3 rounded text-sm mb-4 text-white focus:border-red-600 outline-none">
                <input type="text" id="reg-cedula" placeholder="Cédula de Identidad" class="w-full bg-black border border-gray-700 p-3 rounded text-sm mb-4 text-white focus:border-red-600 outline-none">
                <input type="password" id="reg-pass" placeholder="Contraseña" class="w-full bg-black border border-gray-700 p-3 rounded text-sm mb-6 text-white focus:border-red-600 outline-none">
                <button onclick="registrarCliente()" class="w-full bg-red-600 hover:bg-red-700 text-white p-3 rounded font-black text-sm uppercase transition shadow-lg">Registrarse</button>
                <p class="text-xs text-gray-400 mt-4">¿Ya tienes cuenta? <a href="javascript:void(0);" class="text-red-500 font-bold" onclick="mostrarPantalla('loginScreen')">Inicia sesión</a></p>
            </div>
        </div>

        <!-- 4. PANTALLA DE LOGIN CLIENTE -->
        <div id="loginScreen" class="hidden flex-1 flex items-center justify-center p-4">
            <div class="bg-gray-900/95 border border-red-900/50 p-8 rounded-xl shadow-2xl max-w-md w-full text-center">
                <h2 class="text-xl font-bold uppercase mb-2 text-white">Inicia Sesión</h2>
                <input type="email" id="login-email" placeholder="Correo registrado" class="w-full bg-black border border-gray-700 p-3 rounded text-sm mb-4 text-white focus:border-red-600 outline-none">
                <input type="password" id="login-pass" placeholder="Contraseña" class="w-full bg-black border border-gray-700 p-3 rounded text-sm mb-6 text-white focus:border-red-600 outline-none">
                <button onclick="iniciarSesionCliente()" class="w-full bg-red-600 hover:bg-red-700 text-white p-3 rounded font-black text-sm uppercase transition shadow-lg">Entrar</button>
                <p class="text-xs text-gray-400 mt-4">¿No tienes cuenta? <a href="javascript:void(0);" class="text-red-500 font-bold" onclick="mostrarPantalla('registerScreen')">Regístrate</a></p>
            </div>
        </div>

        <!-- 5. PANEL DEL CLIENTE -->
        <div id="clientPanel" class="hidden flex-1 flex flex-col md:flex-row w-full max-w-7xl mx-auto">
            <aside class="w-full md:w-64 bg-gray-900 border-r border-gray-800 p-4 flex flex-col space-y-6">
                <div>
                    <p class="text-xs text-gray-500 uppercase tracking-wider font-bold mb-3">Navegación</p>
                    <nav class="space-y-1">
                        <button onclick="cambiarSeccionCliente('resumen')" id="navResumen" class="w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold bg-red-600 text-white transition"><span>🏠</span> <span>Resumen</span></button>
                        <button onclick="cambiarSeccionCliente('catalogo')" id="navCatalogo" class="w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold text-gray-400 hover:bg-gray-800 hover:text-white transition"><span>🛒</span> <span>Catálogo &amp; Compras</span></button>
                        <button onclick="cambiarSeccionCliente('transacciones')" id="navTransacciones" class="w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold text-gray-400 hover:bg-gray-800 hover:text-white transition"><span>📄</span> <span>Transacciones</span></button>
                    </nav>
                </div>
                <div>
                    <p class="text-xs text-gray-500 uppercase tracking-wider font-bold mb-3">Recargas</p>
                    <nav class="space-y-1">
                        <button onclick="cambiarSeccionCliente('reportarPago')" id="navReportar" class="w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold text-gray-400 hover:bg-gray-800 hover:text-white transition"><span>💳</span> <span>Reportar Pago Móvil</span></button>
                    </nav>
                </div>
                <div>
                    <p class="text-xs text-gray-500 uppercase tracking-wider font-bold mb-3">Mi Cuenta</p>
                    <nav class="space-y-1">
                        <button onclick="cambiarSeccionCliente('miPerfil')" id="navPerfil" class="w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold text-gray-400 hover:bg-gray-800 hover:text-white transition"><span>👤</span> <span>Mi Perfil</span></button>
                    </nav>
                </div>
            </aside>

            <div class="flex-1 p-4 md:p-8 overflow-y-auto">
                <!-- Resumen -->
                <div id="viewResumen" class="space-y-6">
                    <div class="flex justify-between items-center bg-gray-900 border border-gray-800 p-6 rounded-xl flex-wrap gap-4">
                        <div>
                            <h2 class="text-2xl font-black text-white">¡Bienvenido, <span id="clientEmailHeader" class="text-red-500">Cliente</span>!</h2>
                            <p class="text-xs text-gray-400 mt-1">Consulta tu saldo y estado de cuenta al instante.</p>
                        </div>
                        <button onclick="cambiarSeccionCliente('reportarPago')" class="bg-red-600 hover:bg-red-700 text-white text-xs font-bold px-4 py-2.5 rounded shadow">RECARGA TU CUENTA</button>
                    </div>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="bg-gray-900 border border-gray-800 p-5 rounded-xl border-l-4 border-l-green-500">
                            <p class="text-xs text-gray-400 uppercase font-semibold">Saldo actual disponible</p>
                            <h3 class="text-3xl font-black text-green-400 mt-2" id="clientActualSaldo">$0.00</h3>
                        </div>
                    </div>
                    <div class="bg-gray-900 border border-gray-800 p-6 rounded-xl">
                        <h3 class="text-sm font-bold uppercase mb-4 text-gray-300">Movimientos Recientes</h3>
                        <div id="clientHistoryList" class="space-y-2 max-h-60 overflow-y-auto pr-2"></div>
                    </div>
                </div>

                <!-- Catálogo -->
                <div id="viewCatalogo" class="hidden space-y-6">
                    <div class="flex justify-between items-center bg-gray-900 border border-gray-800 p-6 rounded-xl">
                        <h2 class="text-xl font-bold text-white">Catálogo de Servicios</h2>
                        <div class="bg-gray-800 border border-green-600 px-4 py-2 rounded-lg text-green-400 font-bold text-sm" id="catalogWalletBadge">Saldo: $0.00</div>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                        <div class="bg-gray-900 border border-gray-800 rounded-xl p-5 flex flex-col justify-between">
                            <div>
                                <span class="text-xs bg-red-900 text-red-300 px-2 py-0.5 rounded font-bold">PanaXtreaming</span>
                                <h4 class="font-bold text-lg text-white mt-2">Cuenta Completa</h4>
                                <p class="text-xs text-gray-400 my-3">Acceso total con máxima estabilidad.</p>
                            </div>
                            <div>
                                <div class="text-xl font-black text-white mb-3">8$</div>
                                <button onclick="comprarConSaldo('Cuenta Completa', 8)" class="w-full bg-red-600 hover:bg-red-700 text-white font-bold text-xs uppercase py-2.5 rounded">Comprar</button>
                            </div>
                        </div>
                        <div class="bg-gray-900 border border-gray-800 rounded-xl p-5 flex flex-col justify-between">
                            <div>
                                <span class="text-xs bg-red-900 text-red-300 px-2 py-0.5 rounded font-bold">ST3TLLA TV</span>
                                <h4 class="font-bold text-lg text-white mt-2">ST3TLLA TV Completa</h4>
                                <p class="text-xs text-gray-400 my-3">Programación en vivo en HD.</p>
                            </div>
                            <div>
                                <div class="text-xl font-black text-white mb-3">10$</div>
                                <button onclick="comprarConSaldo('ST3TLLA TV Completa', 10)" class="w-full bg-red-600 hover:bg-red-700 text-white font-bold text-xs uppercase py-2.5 rounded">Comprar</button>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Transacciones -->
                <div id="viewTransacciones" class="hidden space-y-6">
                    <div class="bg-gray-900 border border-gray-800 p-6 rounded-xl">
                        <h2 class="text-xl font-bold text-white mb-4">Historial Completo</h2>
                        <div id="fullTransactionsList" class="space-y-3"></div>
                    </div>
                </div>

                <!-- Reportar Pago Móvil -->
                <div id="viewReportarPago" class="hidden space-y-6 max-w-xl mx-auto">
                    <div class="bg-gray-900 border border-gray-800 p-6 rounded-xl">
                        <h2 class="text-xl font-bold text-white mb-2">Reportar Pago Móvil</h2>
                        <div class="bg-black/40 border border-gray-800 p-4 rounded-lg text-xs space-y-1 mb-6 text-gray-300">
                            <p><strong>Banco:</strong> Provincial</p>
                            <p><strong>Pago Móvil:</strong> 0412-2753916</p>
                        </div>
                        <div class="space-y-4">
                            <div>
                                <label class="text-xs text-gray-400 block mb-1">Monto en $ a recargar:</label>
                                <input type="number" id="reportMonto" placeholder="Ej: 10" class="w-full bg-black border border-gray-700 p-3 rounded text-sm text-white outline-none">
                            </div>
                            <div>
                                <label class="text-xs text-gray-400 block mb-1">Últimos 4 dígitos de la referencia:</label>
                                <input type="text" id="reportRef" placeholder="Ej: 4125" class="w-full bg-black border border-gray-700 p-3 rounded text-sm text-white outline-none">
                            </div>
                            <button onclick="enviarReportePago()" class="w-full bg-red-600 hover:bg-red-700 text-white font-black text-sm uppercase p-3 rounded transition shadow">Enviar Reporte al Administrador</button>
                        </div>
                    </div>
                </div>

                <!-- Mi Perfil -->
                <div id="viewMiPerfil" class="hidden space-y-6 max-w-xl mx-auto">
                    <div class="bg-gray-900 border border-gray-800 p-6 rounded-xl">
                        <h2 class="text-xl font-bold text-white mb-4">Perfil de Usuario</h2>
                        <p class="text-sm"><strong>Correo:</strong> <span id="perfilEmail" class="text-gray-300"></span></p>
                    </div>
                </div>
            </div>
        </div>

        <!-- 6. PANEL DE ADMINISTRADOR -->
        <div id="adminPanel" class="hidden flex-1 p-6 max-w-6xl mx-auto w-full">
            <div class="flex justify-between items-center mb-6 bg-gray-900 border border-gray-800 p-6 rounded-xl flex-wrap gap-4">
                <div>
                    <h2 class="text-2xl font-black text-green-400">🛡️ Panel de Administración</h2>
                    <p class="text-xs text-gray-400 mt-1">Aquí llegan los reportes de pago enviados por los usuarios para su aprobación.</p>
                </div>
                <button onclick="cerrarSesion()" class="bg-gray-800 hover:bg-gray-700 border border-gray-700 text-white text-xs font-bold px-4 py-2 rounded">Cerrar Sesión Admin</button>
            </div>

            <!-- Solicitudes de pago pendientes -->
            <div class="bg-gray-900 border border-gray-800 p-6 rounded-xl mb-6">
                <h3 class="text-sm font-bold uppercase mb-4 text-yellow-400">🔔 Solicitudes y Reportes Pendientes</h3>
                <div class="overflow-x-auto">
                    <table class="w-full text-left text-xs border-collapse">
                        <thead>
                            <tr class="bg-gray-800 text-gray-300 border-b border-gray-700">
                                <th class="p-3">Cliente</th>
                                <th class="p-3">Monto</th>
                                <th class="p-3">Referencia</th>
                                <th class="p-3">Fecha</th>
                                <th class="p-3">Acción</th>
                            </tr>
                        </thead>
                        <tbody id="adminOrdersTableBody"></tbody>
                    </table>
                </div>
            </div>

            <!-- Clientes registrados -->
            <div class="bg-gray-900 border border-gray-800 p-6 rounded-xl">
                <h3 class="text-sm font-bold uppercase mb-4 text-gray-300">👥 Clientes Registrados &amp; Saldos</h3>
                <div class="overflow-x-auto">
                    <table class="w-full text-left text-xs border-collapse">
                        <thead>
                            <tr class="bg-gray-800 text-gray-300 border-b border-gray-700">
                                <th class="p-3">Correo</th>
                                <th class="p-3">Saldo Actual</th>
                                <th class="p-3">Asignar Saldo Manual</th>
                            </tr>
                        </thead>
                        <tbody id="adminClientsTableBody"></tbody>
                    </table>
                </div>
            </div>
        </div>

    </main>

    <!-- SCRIPT DE CONTROL UNIFICADO -->
    <script>
        let dbClientes = JSON.parse(localStorage.getItem('panax_db_clientes')) || [];
        let dbReportes = JSON.parse(localStorage.getItem('panax_db_reportes')) || [];
        let sesionActiva = localStorage.getItem('panax_sesion_activa') || null;
        let adminActivo = localStorage.getItem('panax_admin_activo') === 'true';

        window.onload = function() {
            actualizarEstadoUI();
        };

        function ocultarTodo() {
            document.getElementById('homeHero').style.display = 'none';
            document.getElementById('adminLoginScreen').classList.add('hidden');
            document.getElementById('registerScreen').classList.add('hidden');
            document.getElementById('loginScreen').classList.add('hidden');
            document.getElementById('clientPanel').style.display = 'none';
            document.getElementById('adminPanel').style.display = 'none';
            document.getElementById('topWalletDisplay').style.display = 'none';
            document.getElementById('btnSalirSesion').style.display = 'none';
            document.getElementById('topPublicBtns').style.display = 'flex';
        }

        function mostrarPantalla(id) {
            ocultarTodo();
            if (id === 'homeHero') {
                document.getElementById('homeHero').style.display = 'flex';
            } else {
                document.getElementById(id).classList.remove('hidden');
            }
        }

        function irAlInicio() {
            if (adminActivo) {
                abrirPanelAdmin();
            } else if (sesionActiva) {
                abrirPanelCliente();
            } else {
                mostrarPantalla('homeHero');
            }
        }

        function actualizarEstadoUI() {
            ocultarTodo();
            if (adminActivo) {
                abrirPanelAdmin();
            } else if (sesionActiva) {
                abrirPanelCliente();
            } else {
                mostrarPantalla('homeHero');
            }
        }

        // --- VERIFICACIÓN DE CREDENCIALES ADMIN ---
        function verificarLoginAdmin() {
            let u = document.getElementById('adminUser').value.trim();
            let p = document.getElementById('adminPass').value.trim();

            if(u === 'admin' && p === 'adming1234') {
                adminActivo = true;
                localStorage.setItem('panax_admin_activo', 'true');
                abrirPanelAdmin();
            } else {
                alert('Usuario o contraseña de administrador incorrectos. (Usa: admin / adming1234)');
            }
        }

        // --- REGISTRO Y LOGIN CLIENTES ---
        function empezarRegistroHero() {
            let email = document.getElementById('heroEmail').value.trim();
            if(email) document.getElementById('reg-email').value = email;
            mostrarPantalla('registerScreen');
        }

        function registrarCliente() {
            let email = document.getElementById('reg-email').value.trim().toLowerCase();
            let cedula = document.getElementById('reg-cedula').value.trim();
            let pass = document.getElementById('reg-pass').value.trim();

            if(!email || !cedula || !pass) {
                alert('Completa todos los campos.');
                return;
            }

            if(dbClientes.find(c => c.email === email)) {
                alert('El correo ya está registrado.');
                mostrarPantalla('loginScreen');
                return;
            }

            dbClientes.push({ email, cedula, pass, saldo: 0, historial: [] });
            localStorage.setItem('panax_db_clientes', JSON.stringify(dbClientes));
            alert('¡Registro exitoso! Inicia sesión.');
            mostrarPantalla('loginScreen');
        }

        function iniciarSesionCliente() {
            let email = document.getElementById('login-email').value.trim().toLowerCase();
            let pass = document.getElementById('login-pass').value.trim();

            let cliente = dbClientes.find(c => c.email === email && c.pass === pass);
            if(!cliente) {
                alert('Datos incorrectos.');
                return;
            }

            sesionActiva = email;
            localStorage.setItem('panax_sesion_activa', email);
            abrirPanelCliente();
        }

        function cerrarSesion() {
            sesionActiva = null;
            adminActivo = false;
            localStorage.removeItem('panax_sesion_activa');
            localStorage.removeItem('panax_admin_activo');
            actualizarEstadoUI();
        }

        // --- PANEL CLIENTE ---
        function abrirPanelCliente() {
            ocultarTodo();
            document.getElementById('clientPanel').style.display = 'flex';
            document.getElementById('topWalletDisplay').style.display = 'flex';
            document.getElementById('btnSalirSesion').style.display = 'block';
            document.getElementById('topPublicBtns').style.display = 'none';

            let cliente = dbClientes.find(c => c.email === sesionActiva);
            if(!cliente) { cerrarSesion(); return; }

            document.getElementById('clientEmailHeader').innerText = cliente.email;
            document.getElementById('topSaldoUsd').innerText = `Saldo: $${cliente.saldo.toFixed(2)}`;
            document.getElementById('clientActualSaldo').innerText = `$${cliente.saldo.toFixed(2)}`;
            document.getElementById('catalogWalletBadge').innerText = `Saldo: $${cliente.saldo.toFixed(2)}`;
            document.getElementById('perfilEmail').innerText = cliente.email;

            let htmlHist = '';
            if(cliente.historial && cliente.historial.length > 0) {
                cliente.historial.slice().reverse().forEach(item => {
                    htmlHist += `<div class="bg-black/40 border border-gray-800 p-3 rounded text-xs flex justify-between items-center">
                        <div><p class="font-bold text-white">${item.concepto}</p><p class="text-gray-500 text-[10px]">${item.fecha}</p></div>
                        <span class="font-bold ${item.tipo === 'recarga' ? 'text-green-400' : 'text-red-400'}">${item.tipo === 'recarga' ? '+' : '-'}$${item.monto.toFixed(2)}</span>
                    </div>`;
                });
            } else {
                htmlHist = '<p class="text-xs text-gray-500">No hay movimientos recientes.</p>';
            }
            document.getElementById('clientHistoryList').innerHTML = htmlHist;
            document.getElementById('fullTransactionsList').innerHTML = htmlHist;

            cambiarSeccionCliente('resumen');
        }

        function cambiarSeccionCliente(seccion) {
            ['viewResumen', 'viewCatalogo', 'viewTransacciones', 'viewReportarPago', 'viewMiPerfil'].forEach(id => {
                document.getElementById(id).classList.add('hidden');
            });
            ['navResumen', 'navCatalogo', 'navTransacciones', 'navReportar', 'navPerfil'].forEach(id => {
                document.getElementById(id).className = "w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold text-gray-400 hover:bg-gray-800 hover:text-white transition";
            });

            if(seccion === 'resumen') {
                document.getElementById('viewResumen').classList.remove('hidden');
                document.getElementById('navResumen').className = "w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold bg-red-600 text-white transition";
            } else if(seccion === 'catalogo') {
                document.getElementById('viewCatalogo').classList.remove('hidden');
                document.getElementById('navCatalogo').className = "w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold bg-red-600 text-white transition";
            } else if(seccion === 'transacciones') {
                document.getElementById('viewTransacciones').classList.remove('hidden');
                document.getElementById('navTransacciones').className = "w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold bg-red-600 text-white transition";
            } else if(seccion === 'reportarPago') {
                document.getElementById('viewReportarPago').classList.remove('hidden');
                document.getElementById('navReportar').className = "w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold bg-red-600 text-white transition";
            } else if(seccion === 'miPerfil') {
                document.getElementById('viewMiPerfil').classList.remove('hidden');
                document.getElementById('navPerfil').className = "w-full flex items-center space-x-3 px-3 py-2.5 rounded-lg text-sm font-semibold bg-red-600 text-white transition";
            }
        }

        function comprarConSaldo(concepto, precio) {
            let cliente = dbClientes.find(c => c.email === sesionActiva);
            if(!cliente) return;
            if(cliente.saldo < precio) {
                alert('Saldo insuficiente.');
                cambiarSeccionCliente('reportarPago');
                return;
            }
            cliente.saldo -= precio;
            cliente.historial.push({ concepto: `Compra: ${concepto}`, monto: precio, tipo: 'compra', fecha: new Date().toLocaleString() });
            localStorage.setItem('panax_db_clientes', JSON.stringify(dbClientes));
            alert(`¡Compra de "${concepto}" realizada con éxito!`);
            abrirPanelCliente();
        }

        function enviarReportePago() {
            let monto = parseFloat(document.getElementById('reportMonto').value);
            let ref = document.getElementById('reportRef').value.trim();

            if(!monto || !ref) {
                alert('Ingresa el monto y la referencia.');
                return;
            }

            dbReportes.push({ id: Date.now(), email: sesionActiva, monto, ref, fecha: new Date().toLocaleString() });
            localStorage.setItem('panax_db_reportes', JSON.stringify(dbReportes));

            alert('¡Reporte enviado al administrador con éxito! En breve será verificado.');
            document.getElementById('reportMonto').value = '';
            document.getElementById('reportRef').value = '';
            cambiarSeccionCliente('resumen');
        }

        // --- PANEL ADMIN ---
        function abrirPanelAdmin() {
            ocultarTodo();
            document.getElementById('adminPanel').style.display = 'block';
            document.getElementById('btnSalirSesion').style.display = 'block';
            document.getElementById('topPublicBtns').style.display = 'none';

            // Cargar solicitudes pendientes
            let htmlOrders = '';
            if(dbReportes.length > 0) {
                dbReportes.forEach((rep, index) => {
                    htmlOrders += `<tr class="border-b border-gray-800">
                        <td class="p-3 text-white">${rep.email}</td>
                        <td class="p-3 text-green-400 font-bold">$${rep.monto.toFixed(2)}</td>
                        <td class="p-3 text-gray-300">${rep.ref}</td>
                        <td class="p-3 text-gray-400 text-[10px]">${rep.fecha}</td>
                        <td class="p-3">
                            <button onclick="aprobarRecarga(${index})" class="bg-green-600 hover:bg-green-700 text-white font-bold px-3 py-1 rounded text-xs">Aprobar y Asignar Saldo</button>
                        </td>
                    </tr>`;
                });
            } else {
                htmlOrders = `<tr><td colspan="5" class="p-4 text-center text-gray-500">No hay solicitudes de recarga pendientes.</td></tr>`;
            }
            document.getElementById('adminOrdersTableBody').innerHTML = htmlOrders;

            // Cargar listado clientes
            let htmlClients = '';
            if(dbClientes.length > 0) {
                dbClientes.forEach(cli => {
                    htmlClients += `<tr class="border-b border-gray-800">
                        <td class="p-3 text-white">${cli.email}</td>
                        <td class="p-3 text-green-400 font-bold">$${cli.saldo.toFixed(2)}</td>
                        <td class="p-3">
                            <button onclick="asignarSaldoDirecto('${cli.email}')" class="bg-blue-600 hover:bg-blue-700 text-white font-bold px-3 py-1 rounded text-xs">+ Asignar Saldo</button>
                        </td>
                    </tr>`;
                });
            } else {
                htmlClients = `<tr><td colspan="3" class="p-4 text-center text-gray-500">No hay clientes registrados.</td></tr>`;
            }
            document.getElementById('adminClientsTableBody').innerHTML = htmlClients;
        }

        function aprobarRecarga(index) {
            let rep = dbReportes[index];
            let cliente = dbClientes.find(c => c.email === rep.email);

            if(cliente) {
                cliente.saldo += rep.monto;
                cliente.historial.push({
                    concepto: `Recarga aprobada (Ref: ${rep.ref})`,
                    monto: rep.monto,
                    tipo: 'recarga',
                    fecha: new Date().toLocaleString()
                });
            }

            dbReportes.splice(index, 1);
            localStorage.setItem('panax_db_clientes', JSON.stringify(dbClientes));
            localStorage.setItem('panax_db_reportes', JSON.stringify(dbReportes));

            alert('¡Saldo aprobado y sumado al cliente exitosamente!');
            abrirPanelAdmin();
        }

        function asignarSaldoDirecto(emailCliente) {
            let monto = parseFloat(prompt(`Monto en $ a sumar a ${emailCliente}:`));
            if(!monto || isNaN(monto) || monto <= 0) return;

            let cliente = dbClientes.find(c => c.email === emailCliente);
            if(cliente) {
                cliente.saldo += monto;
                cliente.historial.push({ concepto: 'Recarga manual administrador', monto, tipo: 'recarga', fecha: new Date().toLocaleString() });
                localStorage.setItem('panax_db_clientes', JSON.stringify(dbClientes));
                alert('¡Saldo asignado correctamente!');
                abrirPanelAdmin();
            }
        }
    </script>
</body>
</html>
