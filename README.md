# OTA updates for a formula car
In this article I'll go through the steps I followed to build a custom transport layer protocol to enable a formula car to receive firmware updates over-the-air.

Before starting with the project development itself, in the next paragraph you can better understand the reasons why I built it in the first place.

## The purpose of the project
In the 2023 season, I participated as a [UniUD E-Racing](https://formulasae.uniud.it/) team member in some [competitions between universities](https://en.wikipedia.org/wiki/Formula_SAE) where students design a formula style race car and compete against other teams.

<figure>
 <img alt="Barcelona-Catalunya circuit, practice area" src="images/practice-area-small.png">
  <figcaption>Fig.1 - Barcelona-Catalunya circuit, practice area.</figcaption>
</figure>

In particular, we took part in the Spanish and Italian competitions as an EV team (i.e. a team that competes with an electric vehicle).

<figure>
 <img alt="Schematic of the car's VCUs" src="images/vcu-schematic.png">
  <figcaption>Fig.2 - Schematic of the car's VCUs.</figcaption>
</figure>
