---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-01-05
type: landing

sections:
  # Developer Hero - Gradient background with name, role, social, and CTAs
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, we're"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "We're interested in"
        strings:
          - "AI for Health"
          - "Sustainability and Transport"
          - "Trust and Ethics"
          - "Autonomous Robots and Agents"
          - "Evolutionary and Adaptive Intelligence"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: View Our Seminar Series
          url: "#seminars"
          icon: arrow-down
        - text: Get In Touch
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]
  
  # Filterable Portfolio - Alpine.js powered project filtering
  - block: portfolio
    id: seminars
    content:
      title: "ACAIRA Seminar Series"
      subtitle: "Our ACAIRA Seminar Series runs every other week at Aston University (Main Building). Room TBD."
      count: 0
      filters:
        folders:
          - seminars
  
  - block: portfolio
    id: events
    content:
      title: "Recent & Upcoming Events"
      subtitle: "Check out some of the events we host at our ACAIRA"
      count: 0
      filters:
        folders:
          - events
      buttons:
        - name: All
          tag: '*'
        - name: AI-Health
          tag: AI-Health
        - name: Sustainability-Transport
          tag: Sustainability-Transport
        - name: Trust-Ethics
          tag: Trust-Ethics
        - name: Robotics
          tag: Robotics
        - name: EvolutionaryAI
          tag: EvolutionaryAI
      default_button_index: 0
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  
  
  # Contact Section
  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Let's build something amazing together"
      text: |-
        Whether you're looking to collaborate, give a seminar talk, or just want to say hi, feel free to reach out!
      email: g.morales@aston.ac.uk
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
---
