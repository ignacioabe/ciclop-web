---
layout: monosite
title: Ciclo-P
menu:
  - title: Funcionalidades
    href: "#funcionalidades"
  - title: Metodología
    href: "#metodología"
  - title: Equipo
    href: "#equipo"
  - title: Contacto
    href: "#contacto"
  - title: Plataforma
    href: "https://app.ciclo-p.cl/"
hero:
  title: ciclo-P
  text: Ciclo-P es una herramienta de predicción de viajes orientada al ciclismo urbano, basada en modelos de demanda de viajes ampliamente utilizados para la planificación de transporte. Permite simular los efectos de un cambio en la población, la superficie construída para distintos usos y las ciclovías en el número de viajes en bicicleta.
  buttons:
    - title: Ir a la plataforma
      href: https://app.ciclo-p.cl/
      type: primary
    - title: Leer el artículo científico
      href: assets/pdf/artículo-final.pdf
      type: secondary
  carousel:
    # El primero tiene que estar activo para que funcione.
    - figure: assets/img/interfaz/zonas-poblacion.png
      active: true
    - figure: assets/img/interfaz/edicion-ciclovias.png
      active: false
    - figure: assets/img/interfaz/zonas-generacion-delta.png
      active: false
    - figure: assets/img/interfaz/arcos.png
      active: false
    - figure: assets/img/interfaz/arcos-delta.png
      active: false
features:
  - title: Crea escenarios urbanos
    icon: buildings
    description: Crea de modo interactivo y sencillo, distintos escenarios urbanos, modificando la población, los usos de suelo y la red de ciclovías.
  - title: Simula los viajes
    icon: map
    description: Simula los viajes en bicicleta, utilizando modelos de demanda de transporte de cuatro etapas (generación de viajes, elección de destino, elección de modo y asignación a la red).
  - title: Visualiza todo
    icon: eye
    description: Visualiza los resultados de la predicción de viajes en distintos mapas, a nivel de zona o calle, para cada uno de los cuatro modelos de demanda simulados.
  - title: Compara escenarios
    icon: files
    description: Compara los resultados de la predicción de demanda de viajes entre distintos escenarios.
explanation:
  title: ¿Cómo funciona?
  parts:
    - title: Modifica los datos explicativos
      description: "Modifica, de modo interactivo y fácil los tres aspectos fundamentales que determinan los viajes en bicicleta:"
      figure: assets/img/amanda-hortiz-WZ6MPDJWH5A-unsplash_recorte.jpg
      figure-caption: Foto de <a href="https://unsplash.com/@amandahortiz?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Amanda Hortiz</a> en <a href="https://unsplash.com/es/fotos/WZ6MPDJWH5A?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
      subparts:
        - title: La población
          description: Aumentando o disminuyendo el total de habitantes o la densidad en cada una de las zonas de modelación.
          icon: people
        - title: La localización de actividades
          description: Modificando el total de metros cuadrados o la densidad de cada uso específico en cada una de las zonas de modelación.
          icon: hospital
        - title: La red de ciclovías
          description: Creando nuevos ejes de ciclovías sobre la red de transporte existente. 
          icon: bicycle
    - title: Simula la demanda de viajes en bicicleta
      description: "La predicción de viajes en bicicleta se realiza mediante un modelo de cuatro etapas: generación de viajes, elección de destino, elección de modo y asignación a la red, enfocado específicamente en los viajes realizados por ciclistas en el ámbito urbano."
      figure: assets/img/clem-onojeghuo-mbZsLMDBPiY-unsplash_recorte.jpg
      figure-caption: Foto de <a href="https://unsplash.com/@clemono?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Clem Onojeghuo</a> en <a href="https://unsplash.com/es/fotos/mbZsLMDBPiY?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
      subparts:
        - title: Generación de viajes
          description: La primera etapa consiste en establecer la generación de viajes, es decir cuántos viajes saldrán desde cada una de las zonas. 
          icon: 1-circle
        - title: Elección de destino
          description: La segunda determina los destinos de los viajes generados, es decir, calcula cuántos viajes se dirigen desde cada una de las zonas hacia todas las demás. Esta etapa también determinará la atracción de viajes (cuántos viajes llegarán a cada una de las zonas).
          icon: 2-circle
        - title: Elección de modo
          description: La tercera etapa establece la cantidad de viajes que se realizarán en bicicleta (desde y hacia cada zona).  
          icon: 3-circle
        - title: Asignación a la red
          description: La cuarta etapa asigna los viajes en bicicleta a la red vial, buscando una ruta eficiente para cada par origen destino. Estas rutas toman en consideración los atributos de la red que afectan su uso en bicicleta (como el tipo de calle, la presencia de ciclovías, la presencia de buses y la pendiente).
          icon: 4-circle
contact:
  title: Si te interesa saber más ¡Contáctanos!
  description: ¿Crees que tu empresa, municipalidad u organización podría aprovechar esta herramienta? ¡No dudes en escribirnos!
  email-name: correo electrónico
  placeholder-message: mensaje
  button: Enviar mensaje
support:
  title: "With the support of:"
  logos:
    - figure: assets/img/logos/CEDEUS.png
    - figure: assets/img/logos/PUC.png
    - figure: assets/img/logos/ANID.png
    - figure: assets/img/logos/cityplanning.png
    - figure: assets/img/logos/GORE.jpg
---

## You're ready to go!

Start developing your Jekyll website.
