---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: 联系我们
      text: |-
        长期招聘科研助理、博士后，欢迎对环境矿物学感兴趣的朋友加入！
      email: 15308428259@163.com
      phone: 888 888 88 88
      address:
        street: 北京市
        city: 海淀区
        region: 颐和园路5号北京大学
        postcode: '100091'
        country: 中国
        country_code: 86
      coordinates:
        latitude: '39.99281'
        longitude: '116.31088'
      directions: 北京大学东连廊203
      office_hours:
        - '周一至周五 9:00 - 18:00'
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
