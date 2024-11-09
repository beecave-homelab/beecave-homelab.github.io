# Het schrijven van goede prompts voor AI

Een prompt is de input die je een AI-model geeft om een specifieke output te krijgen. Het effectief formuleren van een prompt is cruciaal voor het krijgen van relevante en betrouwbare resultaten.

## Inhoudopgave

1. [Introductie](#introductie)
2. [Waarom jij de belangrijkste factor bent bij het werken met AI](#waarom-jij-de-belangrijkste-factor-bent-bij-het-werken-met-ai)
3. [Wat is een prompt?](#wat-is-een-prompt)
4. [Hoe schrijf je een effectieve prompt?](#hoe-schrijf-je-een-effectieve-prompt)
4. [Zelf een goede prompt schrijven (met hulp van AI)](#zelf-een-goede-prompt-schrijven-met-hulp-van-ai)
5. [Een geavanceerde en gestructureerde prompt schrijven (met hulp van AI)](#een-geavanceerde-en-gestructureerde-prompt-schrijven-met-hulp-van-ai)
6. [Meer informatie](#meer-informatie)

## Introductie

Stel dat je een AI-model vraagt om een samenvatting van een boek over psychologie. Je verwacht misschien dat het antwoord precies aansluit bij wat je in gedachten had. Vaak zul je echter merken dat een te brede of vage prompt kan resulteren in een lange, generieke beschrijving zonder diepgang. Door specifieke details en een duidelijke structuur toe te voegen, kun je de kwaliteit van de output aanzienlijk verbeteren.

## Waarom jij de belangrijkste factor bent bij het werken met AI

Hoewel AI krachtige output kan genereren, ben jij altijd de belangrijkste factor voor de kwaliteit van de resultaten. Bijvoorbeeld, stel dat je vraagt om een samenvatting van een wetenschappelijk artikel over klimaatverandering. Als je daarbij specifieke details toevoegt, zoals ‘focus op de belangrijkste conclusies over CO2-reductie en beperk het tot 150 woorden’, zal de AI een veel gerichtere en nuttigere output genereren. Dit laat zien hoe duidelijke, specifieke input de kwaliteit van de output direct kan beïnvloeden.

- **Precies in je input = betere output**: Hoe gedetailleerder je instructies, hoe beter de AI kan presteren. Verwacht niet dat de AI altijd “snapt” wat je bedoelt; wees zo duidelijk mogelijk in wat je wilt.
- **Vertrouw niet blind op AI**: AI-systemen kunnen zogenaamde “hallucinaties” hebben, waarbij ze onjuiste of gefabriceerde informatie genereren. Jij bent altijd verantwoordelijk voor het controleren en valideren van de output.
- **AI als hulpmiddel, niet als vervanging**: AI kan je werk versnellen, vooral door grote hoeveelheden informatie te verwerken, maar vervangt geen inhoudelijke kennis. Menselijke expertise is nodig voor interpretatie en nuance. Hoe beter je zelf bekend bent met het onderwerp, hoe meer je uit AI kunt halen. Als je bijvoorbeeld een lesplan wilt maken, helpt het om zelf ervaring te hebben met lesontwerp en het onderwerp. Zonder die kennis kun je de output van de AI niet goed beoordelen.

## Wat is een prompt?

Een prompt is de instructie die je aan een AI-model geeft om een specifieke reactie of output te krijgen. Het kan variëren van een eenvoudige vraag tot een gedetailleerde opdracht. Hoe je een prompt formuleert, bepaalt de kwaliteit en relevantie van de AI-output. Een goed opgebouwde prompt helpt de AI om de context te begrijpen en zich af te stemmen op je verwachtingen.

## Hoe schrijf je een effectieve prompt?

Stel je voor dat je een meubelstuk wilt monteren zonder handleiding. Je hebt alle onderdelen en gereedschappen, maar zonder duidelijke stappen is het eindresultaat onzeker – mogelijk eindig je met losse schroeven of een wiebelend meubelstuk. Een gedetailleerd stappenplan maakt het daarentegen eenvoudig: je volgt de instructies en weet precies hoe elk onderdeel op zijn plaats valt.

Net als bij het monteren van meubels helpt een goed gestructureerde prompt de AI om jouw vraag nauwkeurig en relevant te beantwoorden. Dit hoofdstuk biedt een stapsgewijze aanpak voor het schrijven van effectieve prompts, zodat je met vertrouwen kunt rekenen op output die aansluit bij je verwachtingen.

### Stappenplan

- **Identificeer doel en context**: Bepaal wat je wilt bereiken met de AI-output en beschrijf de situatie waarin je het gaat gebruiken.
- **Structureer je prompt**: Verdeel de prompt in logische onderdelen voor overzichtelijkheid, bijvoorbeeld met kopjes of nummering.
- **Geef specifieke instructies**: Geef gedetailleerde instructies en voorbeelden om de AI te helpen je verwachtingen te begrijpen.
- **Voorkom verwarring**: Zorg voor heldere taal en volg een logische volgorde om onduidelijkheid te vermijden.
- **Controleer en valideer**: Controleer de output op juistheid en pas de prompt aan indien nodig.

Met deze stappen creëer je een goed gestructureerde prompt, waardoor de AI je vraag beter begrijpt en relevantere output genereert.

## Zelf een goede prompt schrijven

Hieronder zie je een voorbeeld van hoe je een prompt steeds specifieker kunt maken om tot betere resultaten te komen. 

### 1. Een simpele prompt zonder specifieke instructies

Deze prompt is te algemeen en leidt tot een breed, oppervlakkig antwoord.

```markdown
Schrijf een samenvatting van dit hoofdstuk.
```

![simpele prompt](https://github.com/beecave-homelab/beecave-homelab.github.io/blob/main/AI/on_writing_prompts/images/simpele-prompt.gif?raw=true)

[Bekijk de output van deze prompt](https://chatgpt.com/share/672f9f5b-686c-800b-a813-0423d44755de)

### 2. Een specifiekere prompt met enkele instructies

Deze prompt bevat wat context, maar kan nog duidelijker.

```markdown
Schrijf een samenvatting van dit hoofdstuk uit dit boek.
Schrijf de samenvatting volgens een vast format en altijd in vloeiend Nederlands. 
Zorg voor logische overgangen en vloeiende zinnen.
```

![betere prompt](https://github.com/beecave-homelab/beecave-homelab.github.io/blob/main/AI/on_writing_prompts/images/betere-prompt.gif?raw=true)

[Bekijk de output van deze prompt](https://chatgpt.com/share/672f9fb8-fd4c-800b-84f1-16f6defa7708)

### 3. Een nog specifiekere en gedetailleerde prompt

Deze prompt bevat duidelijke instructies en context, wat resulteert in een output die voldoet aan de gestelde eisen.

````markdown
Schrijf een samenvatting van dit hoofdstuk uit dit boek.
Schrijf de samenvatting volgens een vast format en altijd in vloeiend Nederlands. 
De output volgt altijd het onderstaande format:

# FORMAT
```
# {De titel van het hoofdstuk}

## In een zin samengevat

{Schrijf een samenvatting van het hoofdstuk in maximaal 30 woorden} 

## Onderwerp

{Schrijf in twee paragrafen waar het hoofdstuk over gaat}

### De belangrijkste punten

{Schrijf alle belangrijke punten paragrafen waar het hoofdstuk over gaat}

- **{belangrijk punt}**: {Schrijf een korte samenvatting van het belangrijkste punt}
- etc.

## Conclusie

{Schrijf in twee paragrafen de conclusie en aanbevelingen uit het hoofdstuk}

## Keywords and tags

#example-tag #example-key-word
```
````

![gedetailleerde prompt](https://github.com/beecave-homelab/beecave-homelab.github.io/blob/main/AI/on_writing_prompts/images/gedetailleerde-prompt.gif?raw=true)

[Bekijk de output van deze prompt](https://chatgpt.com/share/672f9fd1-3800-800b-8c20-25910e15cb02)

## Een geavanceerde en gestructureerde prompt schrijven (met hulp van AI)

Met de AI-tool [Prompting | Create Pattern (NL)](https://chatgpt.com/g/g-VREBwLDkr-prompting-create-pattern-nl) kun je eenvoudig een geavanceerde prompt opstellen. Hergebruik de prompt uit het vorige onderdeel en ontdek hoe de tool je ondersteunt bij het formuleren van een gedetailleerde prompt. Pas de output zo nodig aan en gebruik dit als een nieuwe prompt om een zeer gerichte vraag aan AI te stellen.

[Bekijk de output van de prompt](https://chatgpt.com/share/672fc68c-8898-800b-a759-5522f8be2b54)

![geavanceerde prompt](https://github.com/beecave-homelab/beecave-homelab.github.io/blob/main/AI/on_writing_prompts/images/geavanceerde-prompt-nl.gif?raw=true)

[Bekijk de output van de prompt](https://chatgpt.com/share/672fd0f9-cf64-800b-8eea-c3e09374346f)


## Meer informatie

- Meer over de aanpak van Fabric voor het schrijven van prompts: [Fabric | Our approach to prompting](https://github.com/danielmiessler/fabric/tree/main?tab=readme-ov-file#our-approach-to-prompting)
- Meer informatie over Markdown: [Markdown Guide](https://www.markdownguide.org/getting-started/)
- CustomGPT prompt-builder tool (EN): [Fabric | Create Custom Pattern](https://chatgpt.com/g/g-QkPXf5bV6-fabric-create-pattern)
- CustomGPT prompt-builder tool (NL): [Prompting | Create Pattern (NL)](https://chatgpt.com/g/g-VREBwLDkr-prompting-create-pattern-nl)
- Voorbeeld van een effectieve prompt voor het samenvatten van een hoofdstuk uit een boek: [GitHub repo met custom-patterns](https://github.com/beecave-homelab/custom-patterns/blob/main/summarize_chapter/system.md)

---
