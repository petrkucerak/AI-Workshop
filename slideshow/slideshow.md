---
marp: true
theme: gaia
_class: lead
style: |
  section {
    font-family: 'Segoe UI', monospace;
    color: #333;
  }
  code {
   font-family: 'Roboto Mono', monospace;
  }
  a {
   color: gray;
  }
  h2 {
    font-size: 1.1rem;
  }
  li{
    font-size: 0.9rem;
  }
  ul {
    margin: 0;
  }
  strong {
    color: #0078d7;
  }
  footer {
    top: 610px;
  }
  header {
    top: 15px;
  }


# header: "![Microsoft Azure](assets/azure.png)"
# footer: "![Studentske Trenerske Centrum](assets/blue.png)"
paginate: true
backgroundColor: "#FFF"
size: 16:9

---

# Artificial Intelligence​
**Co to je a kde se s ní setkáme​?**

<!-- Představení se -->
<!-- Když se řekne AI, co si představíte? -->

---
<!-- 
header: ""
footer: ""
paginate: false
 -->

<!-- DALEE intput: Epic Ilustration of Artificial Intelligence -->

![cover bg](assets/04.png)

---

<!-- DALEE intput: Epic Ilustration of Artificial Intelligence -->

![cover bg](assets/03.png)

---

<!-- DALEE intput: Epic Ilustration of Artificial Intelligence -->

![cover bg](assets/02.png)


---
<!-- 
paginate: true

 -->
# Obsah

- Moderní trendy v AI
- Azure a AI služby
- Jak pracovat na projektu

---

# Oblasti

- finance, big data a predikce dat
- text2speech 
- zpracování obrazu
- třídění pošty, security, ...
- sumarizace textu, chatbots, ...

<!--
OBLASTI
- finance, datová analýza a predikce dat (burza, marketing, rozmístění zboží, ...) Machine Learning a datová analýza, realtime data
- text2speech - syntetizace zvuku
- zpracování obrazu (obličej, text, znaky, účtenky a&nbsp;faktury, ...)
- třídění pošty (SPAM), security
- sumarizace textu, chatbots, ... Rozklíčování záměru zprávy 
- předvídání poruch stroje

-->

---

# Ukázky
## [OpenAI](https://openai.com/)

- https://chat.openai.com/chat - jazykový model
- https://labs.openai.com/ - DALLE 2
- https://designer.microsoft.com/ - Microsft Designer

## Development

- https://github.com/features/copilot
- https://www.tensorflow.org/

<!--

ChatGPT:
- Napiš kód pro otestování rychlosti přenosu paketů v jazyce C.
- Jaký má přínos hra člověče nezlob se pro děti v předškolním věku?

DALLE:
- a ship in the middle of a storm

Designer

-->
---

# Praxe
## Autonomní auta

- obraz
- data
- senzory, CAN bus
- legislativa

![bg right:60% cover](assets/05.png)

<!--
 
Představení osobně 2 nejbližších témat

MĚSTA V PILOTNÍM PROGRAMU

*Ruzne zdroje, ruzne nazory*

- North America
  - Phoenix, Arizona
  - Arlington, Texas
- Europe
  - Stockholm, Sweden
- Asia
  - Singapore
  - Hwaseong, South Korea

-->

---

# Praxe
## Autonomní drony

- distribuovaný systém
- [CTU FEL](https://fel.cvut.cz/cs)
- další doprava 

![bg right:60% cover](assets/07.png)

---

# Praxe
## Průmysl 4.0

IoT, 5G, AI

- sbírání
- data -> znalost
- závěr
- akce

![bg right:60% cover](assets/08.png)

--- 

<!-- Dalle inputMicrosoft Azure 3D ilustration -->

![bg cover](assets/10.png)

---

<!-- Druha část - Azure a AI služby -->

# Azure a AI

- [Azure Applied AI Services](https://azure.microsoft.com/en-us/products/applied-ai-services/#overview)
- [Azure Cognitive Services](https://azure.microsoft.com/en-us/products/cognitive-services/)
- [Azure Machine Learning](https://azure.microsoft.com/en-us/products/machine-learning/#product-overview)
- [AI infrastructure](https://www.microsoft.com/en-us/research/project/ai-at-scale/)

<!--
Na strankach MSFT o Azure AI, 4 kategorie

Otakzaaa?

- AI infrastructures
  - bezi na FPGAckach, kteras se prizpusobuji potrebam vypoctu

-->

---

# Azure Applied AI Services

![bg cover](assets/11.png)

<!--
Azure Applied AI Services (aplikovane sluzby) 
  - Bot Services
  - Form Recognizer
  - Cognitive Search (AI cloud search)
  - Metrics Advisor (sledovani metrik a analyza incidentu)
  - Video Indexor (extrakce vyznamu z audia nebo videoa)
  - Immersive Reader

-->

---

# Azure Cognitive Services

- speech
- language
- vision
- decision
- OpenAI

![bg right:60% cover](assets/12.png)



<!--

DALL-E input: digital art Congitive Services 

Azure Cognitive Services (jake mame smysly, ne doslova)
  - Speech (speech2text, text2speech, speech transaltion, speaker recognition)
  - Language (entity recognition, question answeing, translator, ...)
  - Vision (computer, custom fision, face API)
  - decision (anomaly detector, content moderator, personalizer)
  - Azure openAI Serivces (vyuziti jiz existujicich opensource modelu jako DALL-E 2, GPT-3, ...)
-->

---

# Azure Machine Learning

## Příprava dat

![bg fit](assets/MachineLearningCycle/prepare-data.png)

<!-- 
Azure Machine Learning
  - spracovani datasetu (oznaceni, uprava, kompletovani)
  - civceni a buildeni modelu
    - CLI, Python SDK
    - Notebooks
    - Automated
    - VS Code supports
    - Drag-and/Drop designer
    - Fraimeworks (TenserFlow, PyTorch, ...)
  - deploying a nasazeni do provozu
    - CI/CD pipelines
    - AI endpoins
    - optimalization
    - hybrid and multicloud
    - mode repository
    - prebuilt images
  - monitorovani a sprava
    - policies
    - security
    - error analytics
    - audits
-->
---
# Azure Machine Learning

## Trénování modelu

![bg fit](assets/MachineLearningCycle/build-and-train.png)

<!-- 
Azure Machine Learning
  - spracovani datasetu (oznaceni, uprava, kompletovani)
  - civceni a buildeni modelu
    - CLI, Python SDK
    - Notebooks
    - Automated
    - VS Code supports
    - Drag-and/Drop designer
    - Fraimeworks (TenserFlow, PyTorch, ...)
  - deploying a nasazeni do provozu
    - CI/CD pipelines
    - AI endpoins
    - optimalization
    - hybrid and multicloud
    - mode repository
    - prebuilt images
  - monitorovani a sprava
    - policies
    - security
    - error analytics
    - audits
-->
---
# Azure Machine Learning

## Validování a nasazení

![bg fit](assets/MachineLearningCycle/validate-and-deploy.png)

<!-- 
Azure Machine Learning
  - spracovani datasetu (oznaceni, uprava, kompletovani)
  - civceni a buildeni modelu
    - CLI, Python SDK
    - Notebooks
    - Automated
    - VS Code supports
    - Drag-and/Drop designer
    - Fraimeworks (TenserFlow, PyTorch, ...)
  - deploying a nasazeni do provozu
    - CI/CD pipelines
    - AI endpoins
    - optimalization
    - hybrid and multicloud
    - mode repository
    - prebuilt images
  - monitorovani a sprava
    - policies
    - security
    - error analytics
    - audits
-->
---
# Azure Machine Learning

## Monitorování a správa

![bg fit](assets/MachineLearningCycle/manage-and-monitor.png)

<!-- 
Azure Machine Learning
  - spracovani datasetu (oznaceni, uprava, kompletovani)
  - civceni a buildeni modelu
    - CLI, Python SDK
    - Notebooks
    - Automated
    - VS Code supports
    - Drag-and/Drop designer
    - Fraimeworks (TenserFlow, PyTorch, ...)
  - deploying a nasazeni do provozu
    - CI/CD pipelines
    - AI endpoins
    - optimalization
    - hybrid and multicloud
    - mode repository
    - prebuilt images
  - monitorovani a sprava
    - policies
    - security
    - error analytics
    - audits
-->

---

# Otázky a výzvy

- **etika v účení a používání AI**
- problematika výpočetní síly, *edge computing*
- **datasety pro učení**
- **legislativa a autorská práva**
- transformace pracovních pozic

<!-- 

OTÁZKY A VÝZVY, KTERÉ STOJÍ PŘED NÁMI

- O čem nevíme? Válka přispívá rozvoji, co přinese konflikt na ukrajině?
- Problematika výpočetního výkonu - edge computing
- Problematika data pro učení
- Problematika legislativy - nová osoba v EU
- Transformace pracovních pozic 
 
-->

---

![bg cover](assets/16.png)

<!-- Machine Learning Studio -->

---


# Problémy

- vytvoř ze svého článku na [studuj.digital](https://studuj.digital/) podcast pomocí Azure AI služeb
- uměj naskenovat obash účtenky
- poznej náladu člověk z jeho výrazu
- predikuj výrobu z dat na [Kaggle](https://www.kaggle.com/)
- vycvič model na poznávání typů aut

---

# Navrhovaný postup

1. Brainstorming​
2. Pro a proti ke každému nápadu​
3. Vyberte si ten nejlepší​
4. Udělejte si SWOT analýzu​
5. Připravte koncept​

---

# Praktická část

- Zadání: **Vyřešte pomocí AI problém ve vzdělávacím procesu**
- Kritéria hodnocení:​
  - Relevantnost​
  - Efektivita​
  - Obstání výzev AI​
  - *Způsob prezetování*​

---

![bg cover](assets/17.png)