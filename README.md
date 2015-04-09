<!doctype html>
<html class="no-js">
  <head>
    <meta charset="utf-8">
    <title>"ALMACEN</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width">
    <!-- Place favicon.ico and apple-touch-icon.png in the root directory -->
    <!-- build:css(.) styles/vendor.css -->
    <!-- bower:css -->
    <link rel="stylesheet" href="bower_components/bootstrap/dist/css/bootstrap.css" />
    <link rel="stylesheet" href="bower_components/bootstrap-material-design/dist/css/material.css" />
    <link rel="stylesheet" href="bower_components/bootstrap-material-design/dist/css/ripples.css" />
    <!-- endbower -->
    <!-- endbuild -->
    <!-- build:css(.tmp) styles/main.css -->
    <link rel="stylesheet" href="styles/main.css">
    <link rel="stylesheet" href="bower_components/jquery-easyui-bower/themes/bootstrap/easyui.css">
    <link rel="stylesheet" href="bower_components/jquery-easyui-bower/themes/color.css">
    <link rel="stylesheet" href="bower_components/jquery-easyui-bower/themes/icon.css">
    <link rel="stylesheet" href="bower_components/jquery-easyui-bower/themes/mobile.css">
    <!-- endbuild -->
  </head>
  <body ng-app="adminApp">
    <!--[if lt IE 7]>
      <p class="browsehappy">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
    <![endif]-->

    <!-- Add your site or application content here -->
    

    <div id="wrapper">

        <!-- Sidebar -->
        <div id="sidebar-wrapper">
            <ul class="sidebar-nav">
                <li class="sidebar-brand">
                    <a href="#">
                        Administracion Inventario
                    </a>
                </li>
                <li>
                    <a href="#">Inicio</a>
                </li>
                <li>
                    <a href="#/reserva">Reserva Productos</a>
                </li>
                <li>
                    <a href="#/almacen">Almacen</a>
                </li>
                <li>
                    <a href="#/reportes">Reportes</a>
                </li>
                <li>
                    <a href="#/usuarios">Usuarios</a>
                </li>
                <li>
                    <a href="#/venta">Venta Producto</a>
                </li>
            </ul>
        </div>
        <!-- /#sidebar-wrapper -->

        <!-- Page Content -->
        <div id="page-content-wrapper">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-lg-12">                        
                        <a href="#menu-toggle" class="btn btn-default" id="menu-toggle">Menu</a>
                        
                        <div ng-view=""></div>
                    </div>
                </div>
            </div>
        </div>
        <!-- /#page-content-wrapper -->

    </div>
    <!-- /#wrapper -->	


    <!-- Google Analytics: change UA-XXXXX-X to be your site's ID -->
     <script>
         (function (i, s, o, g, r, a, m) {
             i['GoogleAnalyticsObject'] = r; i[r] = i[r] || function () {
                 (i[r].q = i[r].q || []).push(arguments)
             }, i[r].l = 1 * new Date(); a = s.createElement(o),
             m = s.getElementsByTagName(o)[0]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m)
         })(window, document, 'script', '//www.google-analytics.com/analytics.js', 'ga');

         ga('create', 'UA-XXXXX-X');
         ga('send', 'pageview');
    </script>

    <!-- build:js(.) scripts/oldieshim.js -->
    <!--[if lt IE 9]>
    <script src="bower_components/es5-shim/es5-shim.js"></script>
    <script src="bower_components/json3/lib/json3.js"></script>
    <![endif]-->
    <!-- endbuild -->

    <!-- build:js(.) scripts/vendor.js -->
    <!-- bower:js -->
    <script src="bower_components/jquery/dist/jquery.js"></script>
    <script src="bower_components/angular/angular.js"></script>
    <script src="bower_components/bootstrap/dist/js/bootstrap.js"></script>
    <script src="bower_components/angular-resource/angular-resource.js"></script>
    <script src="bower_components/angular-cookies/angular-cookies.js"></script>
    <script src="bower_components/angular-sanitize/angular-sanitize.js"></script>
    <script src="bower_components/angular-animate/angular-animate.js"></script>
    <script src="bower_components/angular-touch/angular-touch.js"></script>
    <script src="bower_components/angular-route/angular-route.js"></script>
    <script src="bower_components/jquery-easyui-bower/jquery.easyui.min.js"></script>
    <script src="bower_components/bootstrap-material-design/dist/js/material.js"></script>
    <script src="bower_components/bootstrap-material-design/dist/js/ripples.js"></script>
    <!-- endbower -->
    <!-- endbuild -->

        <!-- build:js({.tmp,app}) scripts/scripts.js -->
        <script src="scripts/app.js"></script>
        <script src="scripts/controllers/main.js"></script>
        <script src="scripts/controllers/about.js"></script>
        <script src="scripts/controllers/almacen/almacengrid.js"></script>
        <script src="scripts/controllers/reportes/reportesgrid.js"></script>
        <script src="scripts/controllers/reserva/reservagrid.js"></script>
        <script src="scripts/controllers/usuarios/usuariosgrid.js"></script>
        <script src="scripts/controllers/venta/ventagrid.js"></script>
        
        <script src="scripts/controllers/almacen/productoform.js"></script>
        <script src="scripts/controllers/almacen/stockform.js"></script>
        <script src="scripts/controllers/almacen/unidadform.js"></script>
        
        
        <script src="scripts/controllers/reserva/proveedorform.js"></script>
        <script src="scripts/controllers/reserva/pedidoform.js"></script>
        
        <script src="scripts/controllers/usuarios/usuarioform.js"></script>
        <script src="scripts/controllers/usuarios/administradorform.js"></script>
        
        <script src="scripts/controllers/venta/ventagrid.js"></script>
        
        <!-- endbuild -->
</body>
</html>
