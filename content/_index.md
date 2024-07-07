---
# Leave the homepage title empty to use the site title
title: "Liana Akobian"
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
          filename: header.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        Currently, my focus is on my master thesis at the Zimmer Lab in the realm of computational neuroscience.
        I am applying a cascade of preprocessing techniques for aligning signals from different C. elegans whole brain recordings in order to obtain a low dimensional representation of C. elegans brain activity that is shared across many individuals.
        By modeling the resulting low dimensional representation via dynamical systems, such as Switching Linear Dynamical Systems and its variations, I want to analyze the dynamics that constitute movement.

        **I am looking for a PhD position in a group that allows me to pursue my interest in computational neuroscience.**
        
        When I'm not trying to figure the truths of the world (big emphasis on trying!), I try to portray the truths of my life through art. 


        <p>
        <img src="/assets/media/banner.jpg" width="220" height="240" /> </p>

---
