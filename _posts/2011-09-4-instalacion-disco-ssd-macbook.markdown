---
layout: post
title: Instalación de un disco SSD en un Macbook Pro (mid 2010)
---

Mi último Macbook me duró cuatro años (y todavía sigue prestando servicio en casa de mis padres, como un campeón)  Lógicamente espero lo mismo de mi Macbook Pro 6,2 (mid 2010)  En mi opinión, un portátil Apple puede ser perfectamente útil durante tres o cuatro años (siempre que no tenga problemas de hardware) y la forma más económica de alargar su vida útil es comprar el modelo base (porque las opciones _build to order_ que ofrece Apple son escandalosamente caras) y al cabo de un año o dos  ampliarlo al máximo, o lo que es lo mismo: ampliar la RAM ([esta ha sido la memoria escogida](http://www.alternate.es/html/product/Modulos_de_memoria_DDR3_SO-DIMM/G.Skill/SO-DIMM_8_GB_DDR3-1066_Kit/370349/?tn=APPLEPORTAL&l1=Apple&l2=Memorias), muy bien Alternate por tener una sección con productos _homologados_ para los Mac).

Cosas a plantearse
------------------

En cuanto al disco duro, por supuesto tiene que ser SSD en los tiempos que corren.   En cuanto al tema de los discos SSD hay varias consideraciones a hacer aquí:

* El coste por GB de los discos SSD, si bien ha bajado bastante en los últimos tiempos, sigue siendo notablemente más alto que con los discos duros tradicionales.  

  El tamaño _dulce_ ahora mismo diría que se encuentra en los discos 120GB.  En discos tradicionales diríamos que el año que viene sería el doble, pero con los  SSD pienso cabría esperar dos años hasta que los discos de 240GB se encuentren al precio de los de 120GB a día de hoy.

  Con este tamaño lo que tiene más sentido es comprar un adaptador para la bahía de la unidad Superdrive (estos chismes son conocidos como _optibays_) para usar el disco duro SSD junto con el disco duro que venía de fábrica.  El inventor de esto originalmente fue [MCE](http://www.mcetech.com/optibay/) pero ya se pueden encontrar (con calidad ínfima, eso sí) en eBay por cuatro perras.  

* Por supuesto, aunque dejemos de usar la unidad Superdrive no queremos dejarla arrumbada del todo, así que necesitaremos una carcasa externa con conector USB.

* Snow Leopard no soporta el comando TRIM, por lo que para compensar esto conviene adquirir un disco que incorpore un controlador con una buena gestión de bloques libres.  Esto nos deja con las marcas  que incorporan controladoras Sandforce (aparte de los sempiternos Intel). 

* El Macbook Pro 6,2 (de mediados de 2010) no tiene interfaz SATA 3, por lo que es inútil pagar el sobreprecio de un disco SATA 3. 

* Desmontar un Macbook Pro de aluminio no es algo especialmente difícil, y sólo hace falta un destornillador Philips 00, pero no viene mal tener el resto de destornilladores (por ejemplo los Torx sirven para desmontar los ventiladores, así que aprovechamos para limpiar la suciedad acumulada en un año)  


Y dicho todo esto, quedaba elegir la tienda.  El único sitio que he encontrado donde venden el kit completo (disco SSD + optibay + carcasa para Superdrive + juego de destornilladores) es [MaxUpgrades](http://www.maxupgrades.com/istore/index.cfm?fuseaction=Product.display&product_id=186).  Otros sitio donde comprar es en  [OWC](http://eshop.macsales.com/Search/Search.cfm?Ntk=Primary&Ns=P_Popularity|1&Ne=5000&N=6403&Ntt=Mercury+Electra+6G+120GB) pero el conjunto no incluye la carcasa externa para la Superdrive y además sólo puedes adquirir discos de la marca OWC (que suelen funcionar bastante bien, por lo que he leído por ahí)

El modelo a escoger en MaxUpgrades estaba claro: el OCZ Vertex 2 es el más barato (es tecnología del año pasado con interfaz SATA 2) pero con un controlador Sandforce relativamente reciente.  Los otros modelos a considerar eran el Vertex 3 o Intel 320, pero ambos parece que han tenido recientemenete problemas que requerían actualización de _firmware_.  En todo caso, el Vertex 2 parecía la solución más barata y sólida.

El precio total del _pack_ es de 250 dólares que más 26 gastos de envío por FedEx suponen unos 193 euros en total (a reseñar que el modelo de 120GB en OWC salía por 20$ más)  Tras esto, hubo que pagar 33.67 euros de aduanas al transportista.  El total ha salido por 226 eurazos.   El [precio en Alternate del mismo disco](http://www.alternate.es/html/product/Solid_State_Drive_SATA_de_2,5/OCZ/Vertex2_E_2,5_SSD_120_GB/433828/?) es de 157€ con gastos de envío, así que  podemos decir que la carcasa para Superdrive, el _optibay_ y el juego de destornilladores me ha salido por 70 euros.  No tengo muy claro que haya sido una buena compra... (no supe que habría gastos de aduana)

Entrega e instalación
---------------------

A cambio de no haber hecho quizá la mejor compra del mundo lo demás ha sido bastante cómodo: el pedido ha tardado más o menos unos 8 días en llegar al primer intento de entrega en casa.  Tras conseguir coincidir con el transportista (FedEx envía en España a través de Chronopost), el disco llegó a mis manos en 13 días. 

El paquete destaca por lo frugal, sólo lleva el albarán de entrega a transportista y la nota de aduanas.  En el interior no hay ningún papel, ni guía de instalación, ni factura.  El disco SSD viene ya montado en la carcasa _optibay_ y todo viene más o menos emparedado en la carcasa para la superdrive, supongo que para darle algo de rigidez y protección al paquete.   

Pero lo más decepcionante ha sido el juego de destornilladores.  Como decía antes, desmontar un Macbook Pro Unibody está al alcance de cualquiera siempre que se tenga algo de cuidado y las herramientas correctas.  Pues bien,  el destornillador más importante es el Philips 00 -con el que quitas los tornillos de fuera y los que desmontan la unidad _superdrive_- era bastante malo, tanto que estuve a punto de abocardar totalmente la cabeza de un par de tornillos.  Por tanto, *nota importante*: mejor adquirir por separado el destornillador en una tienda de confianza.  Los destornilladores Torqx que venían en el juego parecían encajar correctamente y no tuve problemas en desmontar los ventiladores para su limpieza.

La guía que he seguido para el montaje de la unidad es [esta](http://forum.notebookreview.com/apple-mac-os-x/479350-ssd-optibay-install-mid-2010-15-unibody.html) Cosas a destacar:

* Si tenemos otro ordenador en casa, carga la guía que vayamos a seguir.  Es una perogrullada, pero cuando despanzurremos el portátil... ya no podemos leer la guía en él ;)
* Es *fundamental* poner algún paño sobre la mesa o de lo contrario la tapa del Macbook se llevará algún arañazo.  Creedme, porque el mío ya tiene uno -no muy visible-.  
* Los tornillos no tienen todo el mismo tamaño.  Apuntar bien donde va cada tornillo que quitamos.

La siguiente pregunta que hay que responder: ¿dónde poner el disco SSD?  ¿En la bahía del disco duro de fábrica o en la de la superdrive?   En mi caso la respuesta estaba clara: en la bahía óptica, con el _optibay_ (vino muy bien que el disco viniese ya atornillado ahí de origen).  Los nuevos Macbook (2011) vienen con SATA III sólo en la bahía del disco duro, no en la de la Superdrive, por lo que si hubiésemos comprado un disco más moderno habríamos tenido que sacarlo del _optibay_ para atornillarlo en la bahía del disco duro.

Instalación del Sistema Operativo
---------------------------------

El siguiente paso es conseguir que el disco SSD sea arrancable.  Para esto podemos optar por instalar el sistema operativo de cero (usando la Superdrive con el DVD, un llavero USB) o bien clonar el disco duro -que seguimos teniendo operativo- sobre el SSD.  Estos son los pasos que seguí:

* Volver a poner la tapa del Macbook sin atornillarla (por si hubiera algo mal apretado) Recordar que en esta situación no podemos llevarnos el portátil de un sitio para otro así que viene bien tener la batería bien cargada (como con carga para un par de horas). 
* Arrancar el ordenador, comprobar que el disco SSD aparece en el Finder e instalar [Carbon Copy Cloner](http://www.bombich.com/index.html)
* Utilizarlo para copiar el disco.  Aquí probablemente tengamos que indicar que no queremos copiar algunos archivos.  Omití los directorios Pictures, Movies, Downloads y Music de mi cuenta.  También obvié la instalación de XCode y me entretuve en purgar temporales y archivos de _log_ en la instalación de Homebrew (en concreto, MongoDB había dejado unos _logs_ preciosos de varios gigas)  Conviene pecar de conservador aquí y omitir todo lo que se pueda, para evitar que el clonado finalice mal por falta de espacio en el disco SSD de destino (aunque Carbon Copy Cloner hace sus comprobaciones, quién sabe qué puede ir mal)
  Logré reducir mi instalación en el disco SSD a 40GB entre sistema operativo y aplicaciones. 
* Realizar la copia propiamente dicha.  Esto lleva como decíamos un par de horas.
* Tras finalizar la copia, si todo ha ido bien, ir a Preferencias > Disco de Arranque y escoger  el disco SSD.

Reiniciar.  ¡Y a correr! 

Ultimos ajustes
---------------

Tras reiniciar el ordenador (y flipar con la velocidad de todo) tenemos que enlazar en la cuenta de nuestro usuario los directorios que dejamos si copiar en el disco original.

{% highlight bash %}
cd /Users/juan
ln -s /Volumes/Macintosh\ HD/Users/juan/Music Music
ln -s /Volumes/Macintosh\ HD/Users/juan/Pictures Pictures
bck-i-search: ln_
{% endhighlight %}

Lo bueno de todo esto es que en el disco duro antiguo sigue quedando una copia de OSX perfectamente botable, por si algún día tenemos algún desastre con el SSD.  El inconveniente es que en nuestras estrategias de _backup_ tendremos que ser conscientes de que tenemos las cosas repartidas en dos discos físicos distintos (ojo con Time Machine!)

Otros consejos que hemos seguido [los enumeran aquí](http://blogs.nullvision.com/?p=275):

* Activar `noatime` en el punto de montaje del SSD.
* Desactivar el indexado Spotlight (no uso Spotlight para casi nada)
* Poner el disco duro en reposo lo antes posible.  Al disco SSD esto le va a dar igual, pero el disco antiguo no necesita estar continuamente en marcha.  Esto ahorra algo de batería y se nota en cuando a reducción de ruido.

Pruebas
-------

A continuación, y a modo de conclusión, los resultados de XBench para un disco y otro:

<small>
<table>
<thead>
	<td></td>
	<td>Hitachi 320GB</td>
	<td>OCZ Vertex 2 120GB</td>
</thead>
<tr>
	<td>Resultado global</td>
	<td>50.94</td>
	<td>264.13</td>
</tr>
<tr>
	<td>Sequential uncached read (4k blocks)</td>
	<td>23.11 MB/sec</td>
	<td>27.10 MB/sec</td>
</tr>
<tr>
	<td>Sequential uncached read (256k blocks)</td>
	<td>62.32MB/sec</td>
	<td>186.75MB/sec</td>
</tr>
<tr>
	<td>Random uncached read (4k blocks)</td>
	<td>0.48 MB/sec</td>
	<td>19.28 MB/sec</td>
</tr>
<tr>
	<td>Random uncached read (256k blocks)</td>
	<td>20.85 MB/sec</td>
	<td>174.07 MB/sec</td>
</tr>
<tr>
	<td>Sequential uncached write (4k blocks)</td>
	<td>67.52 MB/sec</td>
	<td>108.37 MB/sec</td>
</tr>
<tr>
	<td>Sequential uncached write (256k blocks)</td>
	<td>60.60 MB/sec</td>
	<td>100.72 MB/sec</td>
</tr>
<tr>
	<td>Random uncached write (4k blocks)</td>
	<td>1.30 MB/sec </td>
	<td>101.14 MB/sec</td>
</tr>
<tr>
	<td>Random uncached write (256k blocks)</td>
	<td>24.25 MB/sec</td>
	<td>105.48 MB/sec</td>
</tr>

</table>

</small>

  

  









