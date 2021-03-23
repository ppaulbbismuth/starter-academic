---
title: "The eRocket"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Simon Le Berre

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: In *Wowchemy Conference*
#publication_short: In *ICW*

abstract: There is an increasing demand for fast drone deliveries for both consumer’s necessities and medical emergencies. In addition to improve delivery, there have been many developments within space research aiming to reduce global cost. Reusable rockets are regarded as the future of space travel, however, numerous accidents have been observed during landing, making these rockets an unreliable resource for experimentation. This new benchmark system is a reliable platform. It mainly embeds drone and model making components on an electric thrust vectored rocket architecture.

# Summary. An optional shortened abstract.
summary: Fast autonomous flying and reausable rocket platform are now possible thanks to the eRocket. This is a vector electric rocket with contra-rotating motor propulsion.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

There is an increasing demand for fast drone deliveries for both consumer’s necessities and medical emergencies. In addition to improve delivery, there have been many developments within space research aiming to reduce global cost. Reusable rockets are regarded as the future of space travel, however, numerous accidents have been observed during landing, making these rockets an unreliable resource for experimentation. This new benchmark system is a reliable platform. It mainly embeds drone and model making components on an electric thrust vectored rocket architecture.

![alt text](thumbs.jpg "eRocket CAD")

Under its state conditions and using Newton's laws, the equations of motion approximate an inverted pendulum.

![alt text](eq.jpg "eRocket Theorical Model")

It has then been simulated on MATLAB. It proves that a PID control loop allows the system to accurately takeoff, hover and land.

![alt text](sim.jpg "eRocket MATLAB Simulation")

As a proof of concept, a real prototype is under development. It is now time to optimize flight-time and implement transition between hovering and standard flight.

![alt text](prototype.jpg "eRocket Prototypes")