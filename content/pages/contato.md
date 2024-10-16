---
title: Contato
slug: /contato
sections:
  - type: GenericSection
    subtitle: ''
    text: ''
    actions: []
    media:
      type: ImageBlock
      url: /images/WhatsApp Image 2024-10-10 at 16.13.16 (3).jpeg
      altText: Fun feature preview
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        justifyContent: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Quer Fazer Parte Desse Time?
      color: text-dark
      styles:
        self:
          textAlign: center
          fontWeight: 700
    subtitle: Entre em Contato
    text: >+
      <div style="text-align: center">*“Uma oportunidade única de alcançar a
      próxima etapa do seu negócio.”*</div>

    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Nome
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: E-mail
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Mensagem...
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Enviar
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
          justifyContent: center
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
        alignItems: center
      subtitle:
        textAlign: center
  - title:
      text: FAQ
      color: text-dark
      styles:
        self:
          textAlign: center
          fontWeight: 700
      type: TitleBlock
    subtitle: ''
    items:
      - title: Como Podemos Ajudar?
        subtitle: ''
        text: |
          Criando uma estrátegia de Marketing e uma identidade para sua Marca.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Como Funciona?
        subtitle: ''
        text: >
          Após algumas reuniões para identificar o melhor trajeto para sua
          marca, começamos a produzir seu material.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Porque Escolher a Inside?
        subtitle: ''
        text: >
          Acreditamos que o marketing digital é uma ferramenta poderosa que pode
          ajudar empresas de todos os tamanhos a crescer e se destacar no
          mercado.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: Contato
  metaDescription: Contato
  socialImage: /images/WhatsApp Image 2024-10-10 at 16.13.46.jpeg
  type: Seo
  addTitleSuffix: false
type: PageLayout
---
