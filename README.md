<div align="center">
<h1>Tarea 8</h1>
  <p>
    Ingeniería Electrónica · Universidad Santo Tomás
    <br>
    <b>Didier Posse</b>
    <br>
    <em>Primer punto</em>
  </p>
</div>

<hr>

<div align="center">
  <h2>Instalación de Máquinas Virtuales</h2>
</div>

<ol>
  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/93d7e80e-8fad-462a-aafb-bfae5ee9ba79"/></p>
    </div>
    <p>
      Primero, se instala <b>QEMU</b> siguiendo el paso a paso que se dejó en la “Tarea-5”.  
      También se instala <b>Virtual Manager</b>, una herramienta que permite gestionar las máquinas virtuales 
      en un entorno gráfico, haciendo su uso mucho más fácil e intuitivo.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/c56bf092-b92d-47e7-9d7b-662432e4fdc8"/></p>
    </div>
    <p>
      En este paso se realiza todo el proceso de creación de la máquina virtual: seleccionar la ubicación de la imagen <b>(.iso)</b>,
      el sistema operativo a instalar, la cantidad de <b>memoria RAM</b> y los <b>núcleos de CPU</b> que se le asignarán.  
      Con esto configurado, se puede iniciar el arranque del booteable y continuar con la instalación.
    </p>
  </li>
</ol>

<h2>Rocky Linux</h2>

<ol>
  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/e1d671ea-49cd-44ac-b2de-2c13c34058c7"/></p>
    </div>
    <p>
      Después de realizar el proceso con QEMU y Virtual Manager, aparece la pantalla de arranque, donde se elige el tipo de instalación.  
      La primera opción suele ser la <b>default</b> y la más recomendable.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/7c3b7d74-288d-475b-892a-7dcf704d3031"/></p>
    </div>
    <p>
      Aquí se muestra la configuración de la instalación de Rocky Linux.  
      La imagen <b>(.iso)</b> ya reconoce automáticamente el idioma, el teclado y otras configuraciones por defecto.  
      Sin embargo, es necesario elegir el disco donde se almacenará el sistema operativo (el que se asignó desde Virtual Manager).  
      Además, se debe decidir si se habilita la cuenta <b>root</b> y crear el usuario principal con su respectiva contraseña.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/518480eb-3598-49f3-b3a2-b18b1095d38e"/></p>
    </div>
    <p>
      Luego comienza la instalación del sistema operativo según el software seleccionado.  
      Generalmente se deja el modo <b>default</b>, que es una versión más liviana y práctica.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/c573519f-9a81-4698-9803-ee7bc12c6866"/></p>
    </div>
    <p>
      Si todo sale bien, el sistema se reiniciará automáticamente y mostrará el usuario que se creó durante la instalación.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/08ba15d4-6ad7-4c08-810c-7349a8ce1690"/></p>
    </div>
    <p>
      Finalmente, aparece la interfaz principal de Rocky Linux, ofreciendo un pequeño tutorial opcional y la bienvenida en el terminal.
    </p>
  </li>
</ol>

<h2>Kali Linux</h2>

<ol>
  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/b68413ce-5d28-4bbc-9f17-f26bc814783c"/></p>
    </div>
    <p>
      Al iniciar el arranque del booteable, se muestran varias opciones de instalación.  
      Normalmente se recomienda la primera, ya que es la más cómoda y automática.  
      Sin embargo, por error seleccioné la segunda opción, que realiza la instalación mediante consola.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/0b372c81-e021-4189-9421-b515b4156809"/></p>
    </div>
    <p>
      Luego, aparece una interfaz por consola donde se debe escoger el idioma general, el idioma del teclado y la región.  
      Las selecciones se realizan escribiendo el número correspondiente a cada opción.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/c578defc-becb-41cb-a0fc-5ecc8845d4b9"/></p>
    </div>
    <p>
      Tras elegir el idioma y la región, el instalador pide el <b>nombre del dominio</b>, el <b>nombre completo del usuario</b>, 
      el <b>nombre de usuario</b> como tal y finalmente la <b>contraseña</b> para esa cuenta.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/ce92977e-e279-4c42-8001-c8755e1576c9"/></p>
    </div>
    <p>
      A continuación, se muestran las particiones disponibles, donde debe aparecer la que se asignó en Virtual Manager.  
      Se selecciona y se confirma la instalación en esa unidad cuando el sistema lo pregunte por seguridad.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/2aafe68e-5b4e-46e4-8f44-2d4f5d5dda18"/></p>
    </div>
    <p>
      Una vez seleccionada la partición, el sistema la formatea automáticamente y solicita elegir qué tipo de entorno gráfico instalar.  
      <b>GNOME</b> y <b>KDE Plasma</b> son más pesados, así que se recomienda <b>Xfce</b>, que es más liviano.  
      También se pueden instalar las <b>default tools</b> (herramientas más comunes de Kali).
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/b4839564-3a81-48cd-87da-d837c8566d01"/></p>
    </div>
    <p>
      Tras seleccionar las opciones deseadas, el sistema inicia la instalación y, una vez completada, se reinicia para cargar el entorno de Kali Linux.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/f775cc95-2152-4041-9235-c0c70d466f8a"/></p>
    </div>
    <p>
      Finalmente, al iniciar sesión con el usuario y contraseña creados, se muestra la interfaz de inicio con las aplicaciones 
      y herramientas instaladas según la configuración elegida durante la instalación.
    </p>
  </li>
</ol>

<div align="center">
  <h2>Windows</h2>
</div>

<ol>
  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/46fd26a4-7d3c-42e0-a25d-c10563cd96f4"/></p>
    </div>
    <p>
      Al iniciar la instalación de Windows, primero aparecen las opciones de idioma, formato de hora y moneda, y el idioma del teclado.
      Estas configuraciones permiten adaptar el sistema a la región y preferencias del usuario, algo que no todos los sistemas operativos incluyen durante la instalación.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/56c3cd33-eb67-4234-bd10-f83359b9ec35"/></p>
    </div>
    <p>
      Luego se muestra la opción para elegir entre diferentes versiones de Windows 11, como Home, Pro o Education, entre otras.
      En este caso se selecciona <strong>Windows 11 Home</strong> por ser la versión más ligera, ideal para máquinas virtuales (VM),
      ya que consume menos recursos de almacenamiento y hardware. Esto es importante considerando que se instalarán tres máquinas virtuales,
      y solo se necesita lo básico del sistema operativo.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/8d3e54ad-e831-4103-be33-86fd7c93713c"/></p>
    </div>
    <p>
      Después de elegir la versión, el sistema solicita iniciar sesión con una cuenta de Microsoft.
      Esto permite crear una copia de seguridad y realizar una configuración más personalizada del sistema,
      mejorando la experiencia del usuario dentro del entorno Windows.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width="850" src="https://github.com/user-attachments/assets/23d74af0-f606-470f-977b-262e87b2c6fa"/></p>
      <p><img width="850" src="https://github.com/user-attachments/assets/2cd0dedc-1551-44c0-9d91-c5d1bd43751f"/></p>
    </div>
    <p>
      Finalmente, tras completar las configuraciones iniciales, aparece la pantalla de bloqueo de <strong>Windows 11</strong>.
      Una vez dentro, se muestra el escritorio predeterminado, desde donde el usuario puede comenzar a utilizar el sistema operativo de manera normal.
    </p>
  </li>
</ol>

<hr>

<div align="center">
  <p><em>Segundo punto</em></p>
</div>

<hr>

<div align="center">
  <h2>Hacer una red con estas 3 MVs</h2>
</div>

<ol>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/a97e9e8e-feb6-45a4-8e5f-86d37b1bb5b8"/></p>
    </div>
    <p>
      Primero hay que <b>crear un switch virtual</b>, lo cual se puede hacer desde <b>Virtual Manager</b>. Ahí seleccionamos <i>Nueva conexión</i> y, en la parte de <b>redes virtuales</b>, podemos crear, eliminar o configurar una red ya existente. 
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/add9329f-313d-4616-840b-aeaf404c13f4"/></p>
    </div>
    <p>
      Cuando presionamos el símbolo <b>“+”</b> para agregar una nueva red, aparece una ventana donde podemos definir el <b>nombre</b> que queremos darle, el <b>modo</b> en el que funcionará, y el <b>formato de IP</b> (IPv4 o IPv6). 
      El más recomendable —y el que yo usé— fue <b>IPv4</b>. Luego se asigna la dirección IP del switch y, al finalizar, se guarda la configuración. Con eso, <b>el switch virtual queda listo</b>.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/3acd2623-7091-4469-8e5b-5939891072cc"/></p>
    </div>
    <p>
      El siguiente paso es abrir <b>Rocky Linux</b> y asignarle una IP para conectarlo directamente con el switch que acabamos de crear. 
      El comando que se usa es:  
      <code>sudo nmcli con add type ethernet con-name &lt;nombre_del_perfil&gt; ifname ens3 ipv4.addresses &lt;ip&gt;/24</code>.  
      Es importante que la IP que asignemos esté dentro del mismo rango del switch.  
      Luego se activa la conexión con: <code>sudo nmcli con up &lt;nombre_del_perfil&gt;</code>,  
      y se puede verificar que todo esté correcto con: <code>ip link show</code>.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/a9f85425-0baf-4d21-9516-081a6080518a"/></p>
      <p><img width=850 src="https://github.com/user-attachments/assets/2ef8bacb-4417-4d6a-804a-95fa58970b9c"/></p>     
      <p><img width=850 src="https://github.com/user-attachments/assets/74449929-3443-446b-8e75-b69ad4e2ec7b"/></p>
    </div>
    <p>
      Otra forma de hacerlo es de una manera más <b>gráfica e intuitiva</b>, usando el comando <code>sudo nmtui</code>.  
      Aunque al principio puede parecer un poco confuso, solo hay que entrar en <i>Modificar conexión</i>, donde se muestran las redes disponibles.  
      Ahí se puede <b>agregar una nueva red</b>, definir el <b>nombre del perfil</b> y el <b>dispositivo</b> (por ejemplo, <code>ens3</code>, <code>eth0</code> o <code>enp1s0</code>, que son nombres de interfaces de red).  
      En mi caso era <code>ens3</code>. Finalmente, solo queda asignar la dirección IP en formato IPv4 y guardar los cambios.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/b2602c65-d2ad-4486-a719-bcf0cb6fa555"/></p>
    </div>
    <p>
      En <b>Kali Linux</b> el proceso es muy similar, aunque el <b>nombre de la interfaz de red</b> suele ser diferente al de Rocky.  
      Es importante tener eso en cuenta, pero el procedimiento para agregar la IP es prácticamente el mismo.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/301d8725-b447-478e-8393-8b8584ee5307"/></p>
    </div>
    <p>
      En <b>Windows</b> el proceso es más <b>fácil y visual</b>.  
      Solo hay que ir a <i>Configuración → Red e Internet</i>, y desde ahí se puede asignar o modificar la IP como se muestra en la imagen.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/dad3ea7b-bc47-4e34-b620-31911b25a71f"/></p>
    </div>
    <p>
      Luego simplemente se asigna la <b>IP deseada</b> junto con la <b>máscara de red</b>.  
      Los demás campos no son necesarios, así que solo se aplican los cambios y la configuración queda lista.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/9c1aa796-3c75-4c21-bfa4-980d3f975eed"/></p>
    </div>
    <p>
      Con el comando <code>ipconfig</code> se puede verificar qué IP tiene asignada la red y confirmar que es la que configuramos.  
      Después de revisar las IP de cada sistema operativo y encender todas las máquinas virtuales, se puede usar <code>ping &lt;ip&gt;</code> para comprobar si <b>hay conexión entre ellas</b> y confirmar que están en la misma red.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/d8739909-68d7-43a8-ac9c-6be278f602fd"/></p>
    </div>
    <p>
      En esta imagen se puede ver cómo <b>Kali</b> hace ping a las otras dos máquinas virtuales, mostrando que efectivamente <b>todas están conectadas en la misma red</b>.
    </p>
  </li>

  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/82a8b662-4cbd-4614-8b64-a25526b1b751"/></p>
    </div>
    <p>
      Finalmente, aquí se muestra cómo <b>Rocky Linux</b> realiza el mismo ensayo y obtiene respuestas positivas, lo que confirma nuevamente que las tres máquinas están comunicándose correctamente dentro de la misma red.
    </p>
  </li>
</ol>
