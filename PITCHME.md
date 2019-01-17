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


@title[LoRaWAN]
+++?image=template/img/LoRaWAN-Overview.png&size=65%

---
@title[Radio]

@snap[north-west]
Radio
@snapend

@snap[west list-content-verbose span-100] 
<br>
@ul[](false)

- Les **protocoles radio** sont définis par [Lora Alliance](https://lora-alliance.org/)  

- Les **Bandes de Fréquences** utilisées par LoRa en Europe sont 863-870 MHz. Ces fréquences sont utilisables par tous, sans conditions de license.

- Les **Cycles d'utilisation** imposés par le régulateur sont de 1% voire 0.1% selon les sous-bandes. Ceci implique d'avoir un réseau performant qui optimise l'envoi des données sur les canaux les moins chargé. Les développeurs doivent optimiser les messages transmis et les fréquences d'émission.

@ulend
@snapend
---

@title[Modulation et taux de transfert]
@snap[north-west]
Modulation et taux de transfert 
@snapend


@snap[west list-content-verbose span-100] 
<br>
@ul[](false)

- La **modulation** LoRa est basée sur une technologie chirp d'étalement de spectre permettant un bon fonctionnement dans le cas de canaux bruités, de rebonds multiples, d'effet Doppler et ce même à basse puissance.

- Le **taux de transfert** dépend de la largeur de bande utilisée et du facteur d'étalement. Les largeurs des bandes LoRa sont de 125 kHz, 250 kHz ou 500 kHz, selon la région et le plan de fréquence. Le facteur d'étalement est choisit par le terminal. Il influence le temps utilisé pour transmettre une trame
@ulend
@snapend

---
@title[Papiers Académiques]
[Papiers Académiques](https://www.thethingsnetwork.org/docs/lorawan/academic.html)

---
@title[Plan d'adressage Lora]

@snap[north-west] Il existe dans LoRaWAN différents identifiants pour les terminaux, applications et passerelles 
@snapend



@snap[south-west list-content-concise span-100]
@ol
- DevEUI - Identifiant du Terminal sur 64 bit, EUI-64 (unique)
- DevAddr - Adresse du Terminal sur 32 bit (non-unique)
- AppEUI - Identifiant de l'Application sur 64 bit, EUI-64 (unique)
- GatewayEUI - Identifiant de la passerelle sur 64 bit, EUI-64 (unique)
@olend

---
@title[Terminaux]

## Terminaux

Les terminaux LoRaWAN ont un identifiant unique de 64 bits (DevEUI) qui est assigné par le fondeur de la puce. 
Mais ces identifiants peuvent être définis par le code.
Cependant les communications sont faites à l'aide d'une adresse dynamique sur 32 bits (DevAddr). 7 bits sont définis pour The Things Network, les 25 restants sont attribués à chaque teminal lors de la procédure appelée **Activation** 


## Over-the-Air Activation (OTAA)

Over-the-Air Activation (OTAA) est la manière préférée et sécurisée pour de se connecter avecThe Things Network. 
Les terminaux effectuent une procédure d'attachement au réseau, au cours de laquelle une DevAddr et des clés de sécurité sont échangées.

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
