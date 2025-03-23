---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Estudio AJO
      text: Transformamos tus ideas en soluciones digitales que facilitan la gestión de tu negocio y te ayudan a crecer.
      primary_action:
        text: ¡Contáctanos y comencemos a trabajar juntos en tu próximo proyecto digital!
        url: #contacto
        icon: rocket-launch
      #secondary_action:
       # text: Read the docs
        #url: https://docs.hugoblox.com
      #announcement:
       # text: "Announcing the release of version 1."
        #link:
         # text: "Read more"
          #url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "black"
        #image:
         # # Add your image background to `assets/media/`.
          #filename: backgruond.svg
          #filters:
          #  brightness: 0.5
 # - block: stats
  #  content:
   #   items:
    #    - statistic: "1M+"
     #     description: |
      #      Websites built  
       #     with Hugo Blox
        #- statistic: "10k+"
         # description: |
          #  GitHub stars  
           # since 2016
      #  - statistic: "3k+"
       #   description: |
        #    Discord community  
         #   for support
    #design:
      # Section background color (CSS class)
     # css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      #spacing:
       # padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Por qué elegirnos
      text: En Estudio Ajo nos especializamos en ofrecer soluciones digitales a medida para pequeñas empresas que buscan optimizar su presencia online y mejorar sus procesos internos. Sabemos que cada negocio tiene sus propias necesidades y desafíos, por eso creamos herramientas digitales personalizadas que se adaptan perfectamente a tus objetivos.
      items:
        - name: Soluciones Personalizadas
          icon: code-bracket
          description: No creemos en una talla única. Trabajamos contigo para entender tus necesidades y ofrecerte soluciones hechas a medida.
        - name: Atención Cercana
          icon: sparkles
          description: En Estudio Ajo, tu negocio es nuestra prioridad. Te acompañamos en cada paso del proceso, asegurándonos de que tus objetivos sean alcanzados.
        - name: Soporte Continuo
          icon: bolt
          description: Nuestro compromiso no termina con la entrega de tu proyecto. Ofrecemos soporte y mantenimiento continuo para asegurarnos de que todo funcione a la perfección.
        #- name: No-Code
         # icon: magnifying-glass
          #description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        #- name: Highly Rated
         # icon: star
          #description: Rated 5-stars by the community.
        #- name: Swappable Blocks
         # icon: rectangle-group
          #description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: servicios
    content:
      items:
        - title: Diseño Web Profesional
          text: Creamos sitios web atractivos, funcionales y fáciles de navegar, diseñados para generar una experiencia de usuario única y convertir visitas en clientes. Ya sea que necesites una página corporativa, una tienda online o un blog, te ayudamos a construir la plataforma ideal para tu negocio.
          feature_icon: code-bracket
          features:
            - Diseño a medida. Creación de sitios web únicos que reflejan la identidad de la marca, adaptados a las necesidades y objetivos específicos del cliente.
            - Rediseño de Páginas Web. Mejoramos y modernizamos sitios web existentes, optimizando su estética y funcionalidad.
          # Upload image to `assets/media/` and reference the filename here
          image: www.jpg
          #button:
          #  text: Get Started
          #  url: https://hugoblox.com/templates/
        - title: Implementaciones de Software a Medida
          text: implementamos aplicaciones y sistemas personalizados que optimizan las operaciones de tu empresa.
          feature_icon: sparkles
          features:
            - Sistemas de Reservas. Facilita la gestión de citas y reservas para tu negocio, con notificaciones automáticas y facilidad para tus clientes.
            - Sistemas de Stock. Mantén el control de tu inventario de manera eficiente, con informes en tiempo real y alertas sobre productos en bajo stock.
            - Sistemas de Ventas. Gestiona tus ventas de manera integrada, desde el seguimiento de pedidos hasta la facturación, todo en un solo lugar.
          # Upload image to `assets/media/` and reference the filename here
          image: implementaciones.jpg
          #button:
          #  text: Join Discord
          #  url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
 # - block: testimonials
  #  content:
   #   title: ""
    #  text: ""
     # items:
      #  - name: "Tedelúpulo"
       #   role: "Dueño"
          # Upload image to `assets/media/` and reference the filename here
       #   image: "testimonial-1.jpg"
       #   text: "...!"
    #design:
    #  spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
    #    padding: ["6rem", 0, 0, 0]
  - block: cta-card
    id: contacto
    content:
      title: ¿Tienes un proyecto en mente?
      text: Nos encantaría ayudarte a hacer realidad tu idea. Ponte en contacto con nosotros y trabajemos juntos para crear una solución digital a medida. Escríbenos a [infoestudioajo@gmail.com](mailto:infoestudioajo@gmail.com)
      #button:
       # text: Get Started
       # url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
       css_class: "dark"
      background:
        color: "black"
---
