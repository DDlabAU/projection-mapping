# Guide til Projektion Mapping

Projektion mapping er en teknik, der bruger software til at projicere billeder eller videoer på ujævne overflader, hvilket forvandler objekter til dynamiske visuelle displays.

<div align="center">

<iframe width="560" height="315" src="https://www.youtube.com/embed/PKMCB5v8pt0?si=aMCVa8xmkMf4ox3R" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</div>

**Video-guide:** [Projektion Mapping med TouchDesigner (YouTube)](https://www.youtube.com/watch?v=E1YMSPLVws0)

## 1. Download TouchDesigner (Gratis Version)

1. Gå til [TouchDesigner Download-side](https://derivative.ca/download).
2. Klik på **Download** under den gratis ikke-kommercielle licens.
3. Installer TouchDesigner på din computer.

## 2. Importer en filmfil

1. Åbn TouchDesigner.
2. Træk en **Movie File In TOP** fra venstre panel ind i dit netværk.
3. Klik på Movie File In-noden og vælg din videofil.

## 3. Brug Kantan Mapper til projektion mapping

1. Højreklik i netværket og tilføj en **Kantan Mapper**-node.
2. Forbind output fra din Movie File In TOP til input på Kantan Mapper.
3. Dobbeltklik på Kantan Mapper for at åbne dens interface.
4. Brug værktøjerne til at tegne former over din projektionsoverflade.
5. Tildel din video til formerne for mapping.

## 4. Forhåndsvis og juster

1. Forbind Kantan Mappers output til en **Window COMP** for at forhåndsvise.
2. Juster former og videoplacering efter behov.
3. Projekter på din fysiske overflade.

