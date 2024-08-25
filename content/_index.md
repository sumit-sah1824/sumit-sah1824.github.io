---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        With a strong foundation in mathematics, I have developed a keen interest in the theoretical aspects of machine learning and artificial intelligence. My work aims to advance the understanding and application of optimization techniques in decentralized and federated learning environments, contributing to more efficient and scalable AI systems. My academic journey has equipped me with a diverse skill set, including proficiency in mathematical modelling, algorithm design, and data analysis. I am passionate about pushing the boundaries of current research and exploring innovative solutions to complex problems in AI. In addition to my research, I am committed to sharing knowledge and fostering a collaborative learning environment. I am enthusiastic about teaching and mentoring students, helping them to develop a deep understanding of mathematical and computational concepts.


    
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
