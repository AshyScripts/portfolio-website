---
title: ''
date: 2025-11-15
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography
    content:
      username: admin
      text: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      text: |-
        <div style="width: 100%; max-width: 1000px; margin: -2rem auto 0 auto; padding: 0 2rem;">
          <img src="/uploads/cnt-hero.jpg" alt="Carbon nanotube fiber assembly under SEM" style="width: 100%; height: auto; border-radius: 12px; box-shadow: 0 10px 40px rgba(0,0,0,0.3);">
          <p style="text-align: center; margin-top: 1rem; margin-bottom: 0; font-size: 0.9rem; color: #94a3b8; opacity: 0.8;">Carbon nanotube fiber assembly - Scanning Electron Microscopy</p>
        </div>
    design:
      columns: '1'
      css_class: 'hbx-bg-gradient'
      background:
        color: ''
      spacing:
        padding: ['0', '0', '1rem', '0']
  - block: markdown
    content:
      text: |-
        <div style="text-align: center; margin: 2rem 0;">
          <a href="/uploads/ashkan-ghanavati-resume.pdf" target="_blank" style="display: inline-block; padding: 12px 32px; background-color: #6366f1; color: white; text-decoration: none; border-radius: 8px; font-weight: 600; font-size: 1.1rem; transition: background-color 0.2s;">
            📄 Download CV
          </a>
        </div>
    design:
      columns: '1'
  - block: resume-skills
    content:
      title: Technical Skills
      username: admin
    design:
      show_skill_percentage: true
  - block: markdown
    content:
      title: '🎯 Research Focus'
      subtitle: ''
      text: |-
        My research bridges experimental materials science and machine learning. I work with real, noisy experimental data from carbon nanotube fiber assemblies, applying techniques like Bayesian optimization and data-efficient ML strategies to extract maximum insight from limited datasets.
        
        I'm passionate about solving problems where physical intuition meets computational power - where domain knowledge guides algorithms, and algorithms reveal patterns that experiments alone cannot uncover.
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Featured Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      view: resume
---