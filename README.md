<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tienda Minecraft - Stormheart</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@3.4.1/dist/css/bootstrap.min.css">
    <style>
        body {
            background: #222;
            color: #fff;
            background-image: url('https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
        }
        h1, h2, h3, h4, h5, h6 {
            color: #00ffd0 !important;
            text-shadow: 2px 2px 8px #000, 0 0 10px #00ffd0;
        }
        p, li, span, strong, b, label {
            color: #fff !important;
            text-shadow: 1px 1px 4px #000;
        }
        .producto h3 {
            color: #ffd700 !important;
            text-shadow: 1px 1px 6px #000, 0 0 6px #ffd700;
            font-weight: bold;
        }
        .producto p strong, .producto p b {
            color: #00ffd0 !important;
            text-shadow: 1px 1px 4px #000;
        }
        .navbar-brand, .nav-tabs > li > a, .nav-tabs > li.active > a {
            color: #00ffd0 !important;
            text-shadow: 1px 1px 6px #000;
        }
        .alert-info {
            background: rgba(0,255,208,0.15);
            color: #00ffd0 !important;
            border-color: #00ffd0;
            font-weight: bold;
            text-shadow: 1px 1px 4px #000;
        }
        footer {
            color: #ffd700 !important;
            text-shadow: 1px 1px 4px #000;
        }
        .btn-comprar {
            background: linear-gradient(90deg, #00ffd0 0%, #ffd700 100%);
            color: #222 !important;
            border: none;
            font-weight: bold;
            box-shadow: 0 0 10px #00ffd0;
        }
        .btn-comprar:hover {
            background: linear-gradient(90deg, #ffd700 0%, #00ffd0 100%);
            color: #222 !important;
        }
        .tab-content { margin-top: 20px; }
        .producto { background: rgba(51,51,51,0.85); border-radius: 8px; padding: 20px; margin-bottom: 20px; }
        .producto img { width: 100px; }
        .navbar { margin-bottom: 30px; }
    </style>
</head>
<body>
    <nav class="navbar navbar-inverse">
      <div class="container">
        <div class="navbar-header">
          <a class="navbar-brand" href="#">Stormheart Tienda</a>
        </div>
      </div>
    </nav>
    <div class="container">
        <h1 class="text-center" style="color:#00ffd0; text-shadow: 2px 2px 8px #000, 0 0 10px #00ffd0;">
            Tienda de Artículos <span style="color:#ffd700;">Stormheart</span>
        </h1>
        <p class="text-center" style="font-size:20px; color:#ffd700; font-weight:bold; text-shadow: 1px 1px 5px #000;">
            <span class="glyphicon glyphicon-globe"></span>
            <strong>IP del servidor:</strong> <span style="font-family:monospace; color:#fff; background:#333; padding:2px 8px; border-radius:6px;">aun no ahi ip</span>
        </p>
        <p class="text-center" style="font-size:17px; color:#fff; background:rgba(0,0,0,0.5); border-radius:8px; padding:8px 0 8px 0; margin-bottom:20px;">
            <span class="glyphicon glyphicon-shopping-cart" style="color:#00ffd0;"></span>
            Compra <span style="color:#ffd700;">objetos exclusivos</span> para mejorar tu experiencia en el servidor.
        </p>
        
        <!-- Menú de pestañas -->
        <ul class="nav nav-tabs" role="tablist">
            <li class="active"><a href="#rangos" role="tab" data-toggle="tab">Rangos</a></li>
            <li><a href="#items" role="tab" data-toggle="tab">Ítems</a></li>
            <li><a href="#kits" role="tab" data-toggle="tab">Kits</a></li>
        </ul>

        <!-- Contenido de las pestañas -->
        <div class="tab-content">
            <!-- Rangos -->
            <div class="tab-pane active" id="rangos">
                <div class="row">
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/pou/images/8/8d/Pou.png/revision/latest?cb=20220622133315" alt="Rango Pou">
                            <h3>Rango Pou</h3>
                            <p>Obtén el rango Pou permanente.</p>
                            <p><strong>$5.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/5" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/6/6a/Gold_Ingot_JE3_BE3.png" alt="Rango VIP">
                            <h3>Rango VIP</h3>
                            <p>Acceso a comandos y zonas exclusivas.</p>
                            <p><strong>$7.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/7" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/7/7e/Emerald_JE3_BE3.png" alt="Rango Élite">
                            <h3>Rango Élite</h3>
                            <p>Beneficios avanzados y kits especiales.</p>
                            <p><strong>$10.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/10" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/5/5e/Diamond_Sword_JE3_BE3.png" alt="Rango Guerrero">
                            <h3>Rango Guerrero</h3>
                            <p>Perfecto para los amantes del PvP.</p>
                            <p><strong>$8.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/8" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/3/3e/Elytra_JE2_BE2.png" alt="Rango Volador">
                            <h3>Rango Volador</h3>
                            <p>¡Vuela por el servidor sin límites!</p>
                            <p><strong>$12.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/12" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/9/9e/Nether_Star_JE2_BE2.png" alt="Rango Legendario">
                            <h3>Rango Legendario</h3>
                            <p>El rango más exclusivo y con más ventajas.</p>
                            <p><strong>$15.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/15" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Ítems -->
            <div class="tab-pane" id="items">
                <div class="row">
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/3/3e/Elytra_JE2_BE2.png" alt="Elytra">
                            <h3>Elytra</h3>
                            <p>Vuela por el mundo con unas elytras exclusivas.</p>
                            <p><strong>$5.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/5" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/2/28/Golden_Apple_JE3_BE3.png" alt="Manzana Dorada">
                            <h3>Manzana Dorada</h3>
                            <p>Recupera vida y obtén efectos especiales con la manzana dorada.</p>
                            <p><strong>$1.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/1" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/5/5e/Diamond_Sword_JE3_BE3.png" alt="Espada de Diamante">
                            <h3>Espada de Diamante</h3>
                            <p>¡Consigue una poderosa espada de diamante encantada!</p>
                            <p><strong>$2.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/2" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <!-- Puedes agregar más ítems aquí -->
                </div>
            </div>
            <!-- Kits -->
            <div class="tab-pane" id="kits">
                <div class="row">
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/5/5e/Diamond_Sword_JE3_BE3.png" alt="Kit Guerrero">
                            <h3>Kit Guerrero</h3>
                            <p>Incluye espada de diamante, armadura y más.</p>
                            <p><strong>$3.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/3" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/4/4e/Iron_Pickaxe_JE3_BE3.png" alt="Kit Minero">
                            <h3>Kit Minero</h3>
                            <p>Herramientas y recursos para minar más rápido.</p>
                            <p><strong>$2.50 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/2.5" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/6/6b/Bow_JE2_BE2.png" alt="Kit Arquero">
                            <h3>Kit Arquero</h3>
                            <p>Arco, flechas y equipamiento para atacar a distancia.</p>
                            <p><strong>$2.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/2" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/2/28/Golden_Apple_JE3_BE3.png" alt="Kit Supervivencia">
                            <h3>Kit Supervivencia</h3>
                            <p>Comida, pociones y manzanas doradas para sobrevivir.</p>
                            <p><strong>$1.50 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/1.5" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/3/3e/Elytra_JE2_BE2.png" alt="Kit Explorador">
                            <h3>Kit Explorador</h3>
                            <p>Elytra, cohetes y brújula para explorar el mundo.</p>
                            <p><strong>$4.00 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/4" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="producto text-center">
                            <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/2/2d/Shield_JE2_BE2.png" alt="Kit Defensor">
                            <h3>Kit Defensor</h3>
                            <p>Escudo, armadura reforzada y pociones de resistencia.</p>
                            <p><strong>$2.75 USD</strong></p>
                            <a href="https://www.paypal.me/LautaroFerreyra587/2.75" class="btn btn-success btn-comprar" target="_blank">Comprar</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="alert alert-info text-center" style="margin-top:30px;">
            <strong>¡Importante!</strong> Después de realizar tu compra, envía tu <b>nombre de usuario de Minecraft</b> y el comprobante de pago a nuestro correo o Discord para recibir tu producto en el servidor.
        </div>
        <hr>
        <p class="text-center">¿Tienes dudas? Contáctanos en <a href="mailto:soporte@stormheart.net">soporte@stormheart.net</a></p>
        <footer class="text-center" style="color:#aaa; margin-top:30px;">
            &copy; 2025 Stormheart. No afiliado con Mojang/Microsoft.
        </footer>
    </div>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@3.4.1/dist/js/bootstrap.min.js"></script>
</body>
</html>
