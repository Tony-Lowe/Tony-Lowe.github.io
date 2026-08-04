---
title: 'Home'
date: 2026-07-26
type: landing

design:
  spacing: '4rem'

sections:
  - block: biography
    content:
      username: me
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      show_status: false
      banner:
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        style: 'text-align: left; font-size: 0.92em; max-width: 44rem;'
      avatar:
        size: large
        shape: rounded
  - block: publications
    content:
      title: Selected Publications
      subtitle: Each thumbnail is an architecture figure from the corresponding paper.
      scholar_url: https://scholar.google.com/citations?user=cpIySUoAAAAJ&hl=en
      items:
        - title: Restore Text First, Enhance Image Later
          venue: CVPR 2026
          description: Two-stage scene text image super-resolution with glyph structure guidance.
          image: media/publications/tiger-pipeline.png
          paper_url: https://arxiv.org/abs/2510.21590
          project_url: https://tony-lowe.github.io/TIGER_project_page/
          code_url: https://github.com/OpenVeraTeam/TiGeSR
          weights_url: https://huggingface.co/mxluocv/TiGeSR
          dataset_url: https://huggingface.co/datasets/mxluocv/UZ-ST
        - title: Beyond Flat Text
          venue: ICCV Workshops 2025
          description: Dual self-inherited guidance for visual text generation.
          image: media/publications/stgen-pipeline.png
          paper_url: https://arxiv.org/abs/2501.05892
          code_url: https://github.com/Tony-Lowe/STGen
        - title: RotationDrag
          venue: arXiv 2024
          description: Point-based image editing with rotated diffusion features.
          image: media/publications/rotationdrag-pipeline.png
          paper_url: https://arxiv.org/abs/2401.06442
          code_url: https://github.com/Tony-Lowe/RotationDrag
  - block: experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: true
  - block: awards
    content:
      title: Selected Honors
      username: me
  - block: markdown
    content:
      title: Languages
      text: |
        **Chinese** — Native speaker<br>
        **English** — C1 (PTE Academic: 88)
---
