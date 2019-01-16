---?color=linear-gradient(to right, #c02425, #f0cb35)
@title[Introduction]

@snap[west text-25 text-bold text-white]
LoRa/TheThingsNetwork<br>*Formation 30 Janvier 2019*
@snapend

@snap[south-west byline text-white text-06]
De l'objet à la donnée...
@snapend

---
@title[The Things Network]

## The Things Network

The Things Network permet à des *objets basse consommation* d'utiliser des *passerelles longue portée* pour se connecter à un réseau
open-source décentralisé afin d'échanger des données avec des *applications*.


![PIC](template/img/architecturettn.png)
<br><br>

---
@title[LoRaWAN]
+++?image=template/img/LoRaWAN-Overview.png

---

@title[Radio]

@snap[west list-content-verbose span-100] 
<br>
@ul[](false)

- Protocoles

Les protocoles radio sont définis par [Lora Alliance](https://lora-alliance.org/)  

- Bandes de Fréquences

En Europe, LoRaWAN utilise la bande 863-870 MHz. Ces fréquences sont utilisables par tous, sans conditions de license.

- Cycles d'utilisation

Le régulateur impose des cycles d'utilisation spécifiques pour chaque sous bande.

Pour les bandes LoRaWAN la valeur est de 1% voire 0.1%.

Ceci implique d'avoir un réseau performant qui optimise l'envoi des données sur les canaux les moins chargé.

Les développeurs doivent optimiser les messages transmis et les fréquences d'émission.

@ulend
@snapend
---

---?include=template/md/split-screen/PITCHME.md

---?include=template/md/sidebar/PITCHME.md

---?include=template/md/list-content/PITCHME.md

---?include=template/md/boxed-text/PITCHME.md

---?include=template/md/image/PITCHME.md

---?include=template/md/sidebox/PITCHME.md

---?include=template/md/code-presenting/PITCHME.md

---?include=template/md/header-footer/PITCHME.md

---?include=template/md/quotation/PITCHME.md

---?include=template/md/announcement/PITCHME.md

---?include=template/md/about/PITCHME.md

---?include=template/md/wrap-up/PITCHME.md

---?image=template/img/presenter.jpg
@title[The Template Docs]

@snap[north-west sign-off]
### **Now it's @color[#e58537](your) turn.**
<br>
#### Quickstart your next slide deck<br>with @size[1.4em](The GitPitch Template).
@snapend

@snap[south docslink text-gold span-100]
For supporting documentation see the [The Template Docs](https://gitpitch.com/docs/the-template)
@snapend
