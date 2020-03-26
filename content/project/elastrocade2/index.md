---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "El Astrocade 2"
summary: "Table-sized version of El Astrocade to promote physical movement and teamwork."
authors: [Felix Dollack, Yuta Kozaki, Takeshi Ozu, Rina Katsube]
tags: [Interactive Gameplay]
categories: []
date: 2020-03-26T01:24:50+09:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Finalized exhibit"
  focal_point: "Bottom"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
The original version of [El Astrocade](../elastrocade/) was limited due to hardware
necessities. For better portability El Astrocade 2 was an attempt to minify the
original game while keeping most of the control aspects the same.

An aluminum frame box with a acrylic display used to project the game from below
was created. The final length of each side of the table was too short to make
players walk. Therefore, we opted for balance control using WiiFit balance boards.
Shifting weight to the left or right side controlled the movement of the spaceship.
Leaning backward on the balance board triggered the shield for defense against damage.

The balance board has a weight limit, so we had to rethink the jump action to
trigger shooting. We decided to build very soft buttons to trigger a shot.
The buttons sense touch by infrared light refraction measured with custom PCB boards
on the inside. Every touch was reflected with a light animation inside the button.

![](ars.jpg)

The work was exhibited during the 5-day lasting [Ars Electronica Festival 2019]
in Linz, Austria. It was well received and a magnet for approximately 1000
visitors a day. The total down-time during the exhibition was less than 5 minutes.

The source code might be released on www.github.com/felixdollack at a later point
after cleaning it a little.

Project status: finished.

[Ars Electronica Festival 2019]: https://ars.electronica.art/outofthebox/en/
