---
layout: monosite
title: Ciclo-P
menu:
  - title: Features
    href: "#funcionalidades"
  - title: Methodology
    href: "#metodología"
  - title: Team
    href: "#equipo"
  - title: Contact
    href: "#contacto"
  - title: Web App
    href: "https://app.ciclo-p.cl/"
hero:
  title: Ciclo-P
  text: Ciclo-P is a travel prediction tool focused on urban cycling, based on travel demand models widely used for transport planning. It allows simulating the effects of a change in population, the built-up area for different uses, and bike lanes on the number of bicycle trips.
  buttons:
    - title: Go to the webapp
      href: https://app.ciclo-p.cl/
      type: primary
    - title: Read the scientific article
      href: /assets/pdf/artículo-final.pdf
      type: secondary
  carousel:
    - figure: /assets/img/interfaz/zonas-poblacion.png
      active: true
    - figure: /assets/img/interfaz/edicion-ciclovias.png
      active: false
    - figure: /assets/img/interfaz/zonas-generacion-delta.png
      active: false
    - figure: /assets/img/interfaz/arcos.png
      active: false
    - figure: /assets/img/interfaz/arcos-delta.png
      active: false
features:
  title: Features
  parts:
    - title: Create urban scenarios
      icon: buildings
      description: Create interactive and easy-to-use urban scenarios by modifying the population, land use, and bike lane network.
    - title: Simulate trips
      icon: map
      description: Simulate bicycle trips using four-stage transport demand models (trip generation, destination choice, mode choice, and assignment to the network).
    - title: Visualize everything
      icon: eye
      description: Visualize travel prediction results on different maps, at the zone or street level, for each of the four simulated demand models.
    - title: Compare scenarios
      icon: files
      description: Compare the results of travel demand predictions between different scenarios.
explanation:
  title: How does it work?
  parts:
    - title: Modify explanatory data
      description: "Interactively and easily modify the three fundamental aspects that determine bicycle trips:"
      figure: /assets/img/amanda-hortiz-WZ6MPDJWH5A-unsplash_recorte.jpg
      figure-caption: Photo by <a href="https://unsplash.com/@amandahortiz?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Amanda Hortiz</a> on <a href="https://unsplash.com/es/fotos/WZ6MPDJWH5A?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
      subparts:
        - title: Population
          description: Increasing or decreasing the total number of inhabitants or the density in each modeling zone.
          icon: people
        - title: Location of activities
          description: Modifying the total square meters or the density of each specific use in each modeling zone.
          icon: hospital
        - title: Bike lane network
          description: Creating new bike lane axes on the existing transport network.
          icon: bicycle
    - title: Simulate bicycle trip demand
      description: "Bicycle trip prediction is performed through a four-stage model: trip generation, destination choice, mode choice, and assignment to the network, specifically focused on urban cycling trips."
      figure: /assets/img/clem-onojeghuo-mbZsLMDBPiY-unsplash_recorte.jpg
      figure-caption: Photo by <a href="https://unsplash.com/@clemono?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Clem Onojeghuo</a> on <a href="https://unsplash.com/es/fotos/mbZsLMDBPiY?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
      subparts:
        - title: Trip generation
          description: The first stage involves establishing trip generation, that is, how many trips will originate from each zone.
          icon: 1-circle
        - title: Destination choice
          description: The second stage determines the destinations of the generated trips, calculating how many trips will go from one zone to all others. This stage also determines trip attraction (how many trips will arrive at each zone).
          icon: 2-circle
        - title: Mode choice
          description: The third stage establishes how many trips will be made by bicycle (to and from each zone).
          icon: 3-circle
        - title: Network assignment
          description: The fourth stage assigns the bicycle trips to the road network, seeking an efficient route for each origin-destination pair. These routes consider network attributes that affect bicycle use (such as street type, bike lanes, bus presence, and slope).
          icon: 4-circle
contact:
  title: If you're interested in learning more, contact us!
  description: Do you think your company, municipality, or organization could benefit from this tool? Don't hesitate to write to us!
  email-name: email
  placeholder-message: message
  button: Send message
support:
  title: "With the support of:"
  logos:
    - figure: /assets/img/logos/CEDEUS.png
    - figure: /assets/img/logos/PUC.png
    - figure: /assets/img/logos/ANID.png
    - figure: /assets/img/logos/cityplanning.png
    - figure: /assets/img/logos/GORE.jpg
---
