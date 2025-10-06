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
  <h2>Instalación de Maquinas Virtuales</h2>
</div>

<ol>
  <li><br>
    <div align="center">
      <p><img <img width=850 src="https://github.com/user-attachments/assets/93d7e80e-8fad-462a-aafb-bfae5ee9ba79"/></p>
    </div>
    <p>
      Primero se instala qemu con el paso a paso que deje en la "Tarea-5", también se instala Virtual Mnager para gestionar las maquinas virtuales que tengamos pero en un entorno gráfico y fácil de usar.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/c56bf092-b92d-47e7-9d7b-662432e4fdc8"/></p>
    </div>
    <p>
      En el siguiente paso, aquí se realiza todo el proceso de creación de la VM, seleccionar la ubicación de la imagen <b>(.iso)</b>, el sistema operativo a instalar, la <b>memoria RAM</b> y los <b>núcleos de CPU</b> que se le asignarán        a la VM.  
      Con eso listo, se puede iniciar el arranque del booteable y continuar con la instalación.
    </p>
  </li>
</ol>

<h2>Rocky Linux</h2>

<ol>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/e1d671ea-49cd-44ac-b2de-2c13c34058c7"/></p>
    </div>
    <p>
      Despuésm de hacer el proceso de qemu y virtual manager, aparece el inicio del arranque donde lo ponen a escoger que instalación quiere hacer, la primera siempre es la default.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/7c3b7d74-288d-475b-892a-7dcf704d3031"/></p>
    </div>
    <p>
      Aquí aparece la configuración de la instalación de Rocky, por la imagen (.iso), ya reconoce el idioma general y el del teclado y otras cosas default, pero uno si debe elegir el disco donde se va a almacenar el sistema operativo, pero ese es el que uno ya le asigno desde virtual manager al so, también te pide la cuenta del root si la quieres tener habilitada o deshabilitada, eso ya va si uno la usara después, y finalmente te pide la cuenta de usuario con su contraseña para poder ingresar al perfil al arrancar Rocky.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/518480eb-3598-49f3-b3a2-b18b1095d38e"/></p>
    </div>
    <p>
      Luego empieza a instalar el sistema operativo según el software que uno escogió, pero por lo general se deja el default como yo lo hize, el default es un software bastante liviano.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850  src="https://github.com/user-attachments/assets/c573519f-9a81-4698-9803-ee7bc12c6866"/></p>
    </div>
    <p>
      Si sale todo bien, se reiniciara el sistema y aparecera el usuario que uno creó.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/08ba15d4-6ad7-4c08-810c-7349a8ce1690"/></p>
    </div>
    <p>
      Ya a lo último debe aparecer la interfaz donde te da la opción de un tutorial si uno lo quiere hacer y la bienvenida en el terminal.
    </p>
  </li>
</ol>

<h2>Kali Linux</h2>

<ol>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/b68413ce-5d28-4bbc-9f17-f26bc814783c"/></p>
    </div>
    <p>
      Primero al iniciar el arranque del booteable, aparece estas opciones de como uno lo quiere instalar, como dije el primero siempre es el más comodo y el default, pero yo por error elegí la segunda opcion que es hacer el proceso de instalación por consola.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/0b372c81-e021-4189-9421-b515b4156809"/></p>
    </div>
    <p>
      Luego, aparece el terminal donde lo pone a escoger el idioma general, el idioma del teclado, la region en la que uno esta, y uno va seleccionando con el número que aparece.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/c578defc-becb-41cb-a0fc-5ecc8845d4b9"/></p>
    </div>
    <p>
      Después de elegir el idioma y la región, te pide colocar el nombre del dominio que uno le quiere colocar, después te pide el nombre completo de la cuenta para el usuario, el nombre como tal del usuario y la contraseña para ese usuario.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/ce92977e-e279-4c42-8001-c8755e1576c9"/></p>
    </div>
    <p>
      Después te aparecen las particiones, donde debe aparecer la que uno le colocó en virtual manager dedicada al sistema operativo, uno finalmente la escoge y te vuelve a preguntar si estas seguro, por seguridad y uno le da que "si".
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/2aafe68e-5b4e-46e4-8f44-2d4f5d5dda18"/></p>
    </div>
    <p>
      Ahí cuando uno ya escoge la partición, el sistema la formatea de forma automatica y nos pregunta que software tanto de apps como de entorno gráfico uno quiere instalarle, GNOME y KDE Plasma son entornos gráficos que consumen muchos recursos, entonces uno elije el Xfce y se puede elejir default tools, las herramientas y apps mas usadas.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/b4839564-3a81-48cd-87da-d837c8566d01"/></p>
    </div>
    <p>
      Ya cuando uno escoge que descargar, hace el proceso de instalación y cuanto termina se reinicia el sistema para que finalmente cargue el sistema operativo que se instaló.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/f775cc95-2152-4041-9235-c0c70d466f8a"/></p>
    </div>
    <p>
      Una vez uno coloca el usuario y la contraseña, aparece la interfaz de inicio con las aplicaciones que se descargaron según el software que uno eligio en la instalacion del SO.
    </p>
  </li>
</ol>

<h2>Windows</h2>

<ol>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/b4839564-3a81-48cd-87da-d837c8566d01"/></p>
    </div>
    <p>
      
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
      Primero hay que crear un switch virtual y esto se puede hacer desde virtual manager, uno coloca nueva conexion, y donde dicen redes virtuales, uno puede crear, eliminar o configurar una red virtual creada.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/add9329f-313d-4616-840b-aeaf404c13f4"/></p>
    </div>
    <p>
      Aqui cuando uno ya le dio al simbolo "+" donde uno agrega la nueva red, aparece el nombre que uno le quiere poner, en que modo quiere que este la red, uno también puede elejir el formato de la ip (IPv4 o IPv6), el recomendale y el que use es el IPv4 y uno pone la ip del switch, después de terminar eso, uno le da a finalizar y ya estaria la parte del switch.
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/3acd2623-7091-4469-8e5b-5939891072cc"/></p>
    </div>
    <p>
      El siguiente paso seria abrir rocky y usar el comando para 
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/a9f85425-0baf-4d21-9516-081a6080518a"/></p>
      <p><img width=850 src="https://github.com/user-attachments/assets/74449929-3443-446b-8e75-b69ad4e2ec7b"/></p>
    </div>
    <p>
      
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/b2602c65-d2ad-4486-a719-bcf0cb6fa555"/></p>
    </div>
    <p>
      
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/301d8725-b447-478e-8393-8b8584ee5307"/></p>
    </div>
    <p>
      
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/dad3ea7b-bc47-4e34-b620-31911b25a71f"/></p>
    </div>
    <p>
      
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/9c1aa796-3c75-4c21-bfa4-980d3f975eed"/></p>
    </div>
    <p>
      
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/d8739909-68d7-43a8-ac9c-6be278f602fd"/></p>
    </div>
    <p>
      
    </p>
  </li>
  <li><br>
    <div align="center">
      <p><img width=850 src="https://github.com/user-attachments/assets/82a8b662-4cbd-4614-8b64-a25526b1b751"/></p>
    </div>
    <p>
      
    </p>
  </li>
</ol>
