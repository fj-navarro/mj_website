---
date: "2022-10-24"
sections:
- block: hero
  content:
    cta:
      label: '**Descarga e-Book GRATIS**'
      url: https://mariaballesteros.netlify.app/pdfs/5_consejos_saludables.pdf
    #cta_alt:
      #label: Ask a question
      #url: https://discord.gg/z8wNYzb
    #cta_note:
      #label: '<div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes"
        #data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star
        #Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button"
        #href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star"
        #data-size="large" data-show-count="true" aria-label="Star">Star the Academic
        #template</a></div>'
    image:
      filename: 5_consejos_portada_verdeclaro.png
    text:
     ¿Siempre a dieta? ¿Te gustaría cambiar tu historia para mantenerte en tu peso y disfrutar de tus comidas de siempre? Descubre las claves para evitar los errores y tomar el control

      <!--Custom spacing-->
      <div class="mb-3"></div>
      <!--GitHub Button JS-->
      <script async defer src="https://buttons.github.io/buttons.js"></script>
    title: 5 Consejos Saludables para Mantenerte en tu Peso
  design:
    background:
      gradient_end: '#00B232'
      gradient_start: '#00B232'
      text_color_light: true
- block: about.biography
  content:
    title: Hola soy María,
    username: maria
  id: about
- block: features
  content:
    items:
    - description: 90%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 100%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 10%
      icon: camera-retro
      icon_pack: fas
      name: Photography
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: GenCoin
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2021-01-01"
      description: |2-
          Responsibilities include:

          * Analysing
          * Modelling
          * Deploying
      location: California
      title: CEO
    - company: University X
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Professor of Semiconductor Physics
    title: Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="recetas" >}}'
    title: Galería
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
#- block: features
  content:
    items:
    - description: "Me encanta este sitio porque ofrece consejos vitales de primera calidad"
      icon: 
      icon_pack: 
      name: Pepe Pérez
    - description: "Una gran web para todos los que quieren mantenerse en su peso y comer muy bien aprendiendo de María"
      icon: 
      icon_pack: 
      name: José Martín
    - description: 10%
      icon: camera-retro
      icon_pack: fas
      name: Photography
    title: Testimonios
- block: contact
  content:
    #address:
      #city: Torrejón de Ardoz
      #country: España
      #country_code: ES
      #postcode: "28850"
      #region: Madrid
      #street: 450 Serra Mall
    #appointment_url: https://calendly.com
    #autolink: true
    contact_links:
    - icon: instagram
      icon_pack: fab
      link: https://instagram.com/mariaygranada
      name: Instagram  
    - icon: youtube
      icon_pack: fab
      link: https://youtube.com/@mariaballesteros_es
      name: Youtube
    - icon: envelope
      icon_pack: fas
      link: "mailto:info@mariaballesteros.es" 
      name: E-mail
    #- icon: twitter
      #icon_pack: fab
      #link: https://twitter.com/Twitter
      #name: DM Me
    #- icon: skype
      #icon_pack: fab
      #link: skype:echo123?call
      #name: Skype Me
    #- icon: video
      #icon_pack: fas
      #link: https://zoom.com
      #name: Zoom Me
    #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    #email: info@mariaballesteros.es
    form:
      #formspree:
        #id: null
      netlify:
        captcha: false
      provider: netlify
    #office_hours:
    #- Monday 10:00 to 13:00
    #- Wednesday 09:00 to 10:00
    #phone: 888 888 88 88
    #subtitle: null
    text: Si quieres ponerte en contacto conmigo puedes rellenar este formulario o escribirme directamente un correo. Te contactaré lo antes posible. 
    title: Contacto
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
