---
title: Publications
#cms_exclude: true
type: landing

design:
  # Default section spacing
  spacing: "1rem"

# # Optional header image (relative to `static/media/` folder).
# banner:
#   caption: ''
#   image: ''

sections:
  - block: collection
    content:
      title: Submitted/In Review
      filters:
        folders:
          - publication
        publication_type: manuscript
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Journal Articles (Peer-Reviewed)
      filters:
        folders:
          - publication
        publication_type: article-journal
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Reports
      text: ""
      filters:
        folders:
          - publication
        publication_type: report
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Dissertation
      text: ""
      filters:
        folders:
          - publication
        publication_type: thesis
        exclude_featured: false
    design:
      view: citation
---
