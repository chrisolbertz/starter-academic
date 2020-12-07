---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Automatisches Testen in Java für Fortgeschrittene (IT-Tage 2020)"
event: IT-Tage
event_url: https://www.ittage.informatik-aktuell.de
location: online
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "Testen mit JUnit oder einem ähnlichen Werkzeug sollte jeder Java-Programmierer beherrschen. In diesem Vortrag werden fortgeschrittenere Werkzeuge für noch besseres Testen vorgestellt."
abstract: "Dieser Vortrag richtet sich an Zuhörer, die bereits Erfahrung mit dem automatischen Testen mit JUnit haben. Neben JUnit selbst existieren zahlreiche weitere Frameworks, die bestimmte Aspekte des Testens vereinfachen oder sogar erst ermöglichen.
Ein großes Problem beim Testen ist, dass auch Tests fehlerhaft sein können. Diesem Problem haben sich mehrere Frameworks angenommen. Eine Hauptursache ist, dass die Tests zu kompliziert werden. AssertJ und Hamcrest möchten dem Abhilfe schaffen, indem sie dabei helfen, so viel Logik wie möglich aus den Tests zu eliminieren und insgesamt die Lesbarkeit der Tests erhöhen.
Mutation-Tests gehen einen anderen Weg. Sie verändern temporär den Quellcode und erzeugen sogenannte Mutanten. Wenn die Tests diese Mutanten nicht entdecken, kann das ein Hinweis auf fehlerhafte Tests sein. Vorgestellt wird das bekannte Java-Framework PiTest. ArchUnit schließlich ermöglicht das Testen von Architekturen. Dabei soll bspw. überprüft werden können, ob sich alle Teammitglieder an vorgegebene Konventionen halten."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-12-08T09:00:00+01:00
date_end: 2020-12-08T09:45:00+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-29T10:02:36+01:00

authors: [Olbertz, Christopher]
tags: [Java, Testen, ArchUnit, Hamcrest, Mutation-Tests, AssertJ]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#   caption: ""
#   focal_point: ""
#   preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
# url_slides:

# url_code:
# url_pdf:
# url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects: []
---
