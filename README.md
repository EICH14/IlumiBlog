  <!DOCTYPE html >
    < html  lang =" es " >
    < cabeza >
        < meta  juego de caracteres =" UTF-8 " >
        < meta  nombre =" ventana gráfica " contenido =" ancho = ancho del dispositivo, escala inicial = 1,0 " >
        < título > BLOG ILUMI </ título >
        < enlace  rel =" hoja de estilo " href =" estilos.css " >
    </cabeza>​​
    < cuerpo >
        <encabezado>​​
            < a  href =" blog.html " > < img  src =" logo.gif " alt =" logo " > </ a >
            <h1> Blog de Ilumi </h1>​​
            < nav >
                < ul >
                    < li > < a  href =" blog.html " > Inicio </ a > </ li >
                    < li > < a  href =" sobre nosotros.html " > Quienes Somos </ a > </ li >
                    < li > < a  href =" contacto.html " > Contactanos </ a > </ li >
                    < li > < a  href =" audiovisual.html " > Contenido Audiovisual </ a > </ li >
                </ul>​​
            </nav>​​
        </encabezado>​​
        < principal >

            < artículo >
            < h2 > ¿QUE ES UN SISTEMA DE INFORMACIÓN DE COMERCIO ELECTRÓNICO? </h2>​​
            <div>​​
                < img  src =" sistema.png " alt =" Imagen de un sistema de comercio electrónico " />
            </div>​​
            < p > Un sistema de información de comercio electrónico es una plataforma tecnológica que facilita la compra y venta de productos y servicios a través de internet.
            < br >
            Estos sistemas integran diversos componentes y funciones para gestionar todas las etapas del proceso de comercio electrónico.
            < br >
Aquí hay una descripción             más detallada : </p>
            <div>​​
                <ol>​​

            < li > Gestión de Catálogo de Productos: Permite a los comerciantes listar y organizar sus productos o servicios, incluyendo descripciones, precios, imágenes y disponibilidad. </li>​​
            < br >
            < li > Carrito de Compras y Procesamiento de Pedidos: Ofrece a los usuarios la capacidad de seleccionar productos, añadirlos a un carrito virtual y proceder al pago.
            Gestiona el proceso de pedido, desde la selección hasta la confirmación de la compra. </li>​​
            < br >
            < li > Pasarelas de Pago: Integra con sistemas de pago para procesar transacciones de manera segura, aceptando tarjetas de crédito, débito, transferencias bancarias y otros métodos de pago. </li>​​
            < br >
            < li > Gestión de Usuarios y Clientes: Maneja las cuentas de los clientes, sus perfiles, historiales de compras y preferencias. Facilitar la autenticación y la personalización de la experiencia de usuario. </li>​​
            < br >
            < li > Logística y Gestión de Inventario: Coordina el almacenamiento, seguimiento y entrega de productos. Actualiza automáticamente el inventario según las ventas y gestiona el cumplimiento de los pedidos. </li>​​
            < br >
            < li > Seguridad y Protección de Datos: Implementa medidas de seguridad para proteger la información sensible de los usuarios y las transacciones, como el cifrado de datos y la autenticación de dos factores. </li>​​
            < br >
            < li > Analítica y Reportes: Proporciona herramientas de análisis para monitorear el rendimiento de ventas, el comportamiento de los usuarios, y otras métricas clave. Ayuda a los comerciantes a tomar decisiones informadas basadas en datos. </li>​​
            < br >
            < li > Marketing y Promociones: Soporta la creación y gestión de campañas de marketing, promociones, descuentos y programas de lealtad para atraer y retener a los clientes. </li>​​
            < br >
            < li > Integración con Otros Sistemas: Conecta con sistemas externos como ERP (Enterprise Resource Planning), CRM (Customer Relationship Management) y plataformas de redes sociales para una operación más fluida y eficiente. </li>​​
            </ol>​​
            </div>​​
            < br >
            < p > En si un sistema de información de comercio electrónico es una solución integral que permite a las empresas llevar a cabo sus actividades comerciales en línea de manera eficiente, segura y efectiva, mejorando la experiencia del cliente y optimizando las operaciones internas. </p>​​
            </ artículo >
            < br >
            < br >

            < artículo >
                < h2 > Aquí hay más temas sobre los sitios de información de comercio electrónico </ h2 >
                < div  class =" contenedor deslizante " >
                    < div  clase =" control deslizante " id =" control deslizante " >
                        < div  class =" slide " > < a  href =" casos de uso.html " > < img  src =" casos de uso.jpg "   alt =" Casos de uso " > </ a > </ div >
                        < div  class =" slide " > < a  href =" interfaz ey s.html " > < img  src =" interfaz ey s.png " alt =" Interfaz e/s " > </ a > </ div >
                        < div  class =" diapositiva " > < img  src =" imagen3.jpg " alt =" Imagen 3 " > </ div >
                    </div>​​
                    < div  class =" botones deslizantes " >
                        < clase de botón  =" botón deslizante " onclick =" moveSlide(-1) " > ◀ </ botón >
                        < clase de botón  =" botón deslizante " onclick =" moveSlide(1) " > ▶ </ botón >
                    </div>​​
                </div>​​
            </ artículo >

            < br >
            < br >
        </principal>​​
        < br >
        < br >
        < pie de página >
            < p > &copia; Blog Ilumi 2024 </p>
        </ pie de página >
        < script  src =" script.js " > </ script >

       < guión >
            dejar  diapositiva actual  =  0 ;

            función  moverDeslizamiento ( dirección )  {
                 control deslizante  constante =  documento . getElementById ( 'control deslizante' ) ;
                 diapositivas  constantes =  documento . querySelectorAll ( '.slide' ) ;
                const  totalDiapositivas  =  diapositivas . longitud ;

                DiapositivaActual  =  ( DiapositivaActual  +  dirección  +  Diapositivas totales )  %  Diapositivas totales ;
                 desplazamiento  constante =  - diapositiva actual  *  100 ;
                control deslizante . estilo . transformar  =  `translateX( ${ offset } %)` ;
            }
        </ guión >

    </cuerpo>​​
    </html>
