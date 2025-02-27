# 🌱 Meesterproef Plantswap 2223

<p style="text-align:center;">
<img src="docs/img/home.png">
</p>

In de Meesterproef heb ik toegepast wat ik in de Minor Web Development hebt geleerd. Voor de Meesterproef kreeg ik samen met mijn team een opdracht van een echte opdrachtgever.

De code van het project is te bekijken op [GitHub](https://github.com/stefanradouane/plantswap), de live versie is te bekijken op [de live demo](https://plantswap.vercel.app/).

Stefan Radouane - 2022-2023 - CMD Amsterdam

## Table of contents

- [Week 1](#week-1)
- [Week 2](#week-2)
- [Week 3](#week-3)
- [Week 4](#week-4)
- [Week 5](#week-5)
- [Reflectie](#reflectie)

## Week 1

We kregen de opdracht 'PlantSwap', het doel hievan was om een website te maken waarop je planten kan ruilen met andere mensen. De opdrachtgever heeft een briefing gegeven en daaruit hebben we een debriefing gemaakt. De debriefing is een document waarin we de opdracht in onze eigen woorden hebben beschreven. Tijdens de brieving hebben we een aantal vragen gesteld, dit zijn een aantal van deze vragen:

### Succescriterea

#### Wat zijn de belangrijkste functies die je wilt zien in de Plant Identifier functie?

1. De Plant Identifier functionaliteit, moet in staat zijn om planten zo nauwkeurig mogelijk te identificeren.
2. De Plant Identifier functionaliteit, moet in staat zijn om na het identificeren van de plant, relevante informatie weer te geven, bijvoorbeeld de naam, lichtbehoeften, waterbehoeften, temperatuur behoeften, type bodem, tips.

#### Wat zijn specifieke doelstellingen of succescriteria definiëren voor deze functie?

- De primaire doelstelling is het vergroten van de sociale cohesie in de buurt, ofwel het dichter bij elkaar brengen van buurtbewoners.
- Een cruciaal doel is het bevorderen van duurzaamheid door het vergroten van kennis over plantenverzorging onder buurtbewoners, wat de noodzaak om nieuwe planten te kopen kan verminderen.

### Gebruiksscenarios

#### Hoe zie je de interactie van gebruikers met de Plant Identifier functionaliteit?

- Gebruikers zouden in staat moeten zijn, hun plant te fotograferen en deze zo te identificeren.
- De Plant Identifier functionaliteit, identificeert de plant en zou relevante informatie over de plant moeten verschaffen.

#### Kun je ons meer vertellen over de gebruikers van deze functionaliteit?

- Voornamelijk buurtbewoners, schatting van mensen vanaf de 30 jaar oud, maar ook bijvoorbeeld door studenten rond de 20 jaar oud.

### Ontwerp

#### Zijn er andere websites of apps met vergelijkbare functies die je bewondert of waarvan je wilt dat we ze als inspiratie gebruiken?

- We zijn vrij om inspiratie te halen uit de andere websites van de buurtcampus, maar het is de bedoeling dat de website een eigen identiteit heeft.

#### Zijn er specifieke ontwerprichtlijnen of stijlgidsen die we moeten volgen bij het ontwerpen van deze functie?

- Geen strikte richtlijnen, maar de huisstijlgids zal beschikbaar worden gesteld.

#### Is er ruimte voor het introduceren van een nieuwe huisstijl of merkimago specifiek voor Plant Swap ?

- Er is ruimte voor het introduceren van een nieuwe huisstijl voor Plant Swap. Er zijn geen strikte richtlijnen, maar de huisstijlgids zal beschikbaar worden gesteld.

### Technische Vereisten

#### Hoe zie je de Plant Identifier functie integreren met de rest van de website?

- De Plant Identifier functie moet geïntegreerd worden in de Plant Swap website.

### User stories

De punten hebben we uiteindelijk omgezet in user stories, dit zijn de belangrijkste user stories:

- Als buurtbewoner van Amsterdam Oost wil ik aan de hand van een foto van een stekje meer informatie over een plant kunnen vinden, zodat ik bij het uploaden van het stekje passende informatie kan toevoegen.
- Als buurtbewoner van Amsterdam Oost wil ik aan de hand van een foto van een plant meer informatie kunnen vinden, zodat ik kan bepalen of het een interessante plant is om een stekje van te kweken.

> We hebben ons aan het begin van het project gefocussed op deze twee user stories later hebben we besloten om ons verder te richten extra user stories.

---

### Feedback week 1

#### Design/code review

### To do week 2

Volgende week ga ik beginnen met het opzetten van de codebase. We hebben er als team voor gekozen om dit te doen met Next.js, omdat de oude codebase ook hierin is geschreven en wij er over aan het twijfelen zijn om deze site te verbeteren of dat wij een eigen site gaan maken.

## Week 2

Het is dus de bedoeling dat we ons grotendeels focussen op de user storie:

> Als buurtbewoner van Amsterdam Oost wil ik, aan de hand van een foto van een stekje, meer informatie over een plant kunnen vinden, zodat ik bij het uploaden van het stekje bijpassende informatie kan toevoegen

We hebben vervolgens allemaal van het team een aantal schetsen gemaakt van de flow, en deze schetsen vervolgens als wireframe te ontwerpen. Ik heb zelf ook een wireframe gemaakt. Het wireframe dat ik heb gemaakt ziet er als volgt uit:

<img src="docs/img/wireflow.png">

De andere uit het team hebben ook wireframes gemaakt,vervolgens heeft @Danian deze wireframes verwerkt tot een eerste versie van de flow.

<img src="docs/img/designs.png">

<img src="docs/img/flow-1.png" >

Ik ben vervolgens aan de slag gegaan om het project te initialiseren. Ik heb een aantal dingen geïnstalleerd en opgezet, zoals:

- [x] [Next.js](https://nextjs.org/)
- [x] [SCSS gekoppeld](https://nextjs.org/docs/app/building-your-application/styling/sass)
- [x] Eerste componenten gemaakt (als voorbeeld voor de andere)
- [x] Eerste pagina's aangemaakt

---

### Feedback week 2

#### Design/code review

Deze week hebben we meer algemene project feedback gehad dan echt design of code review, aangezien we nog echt iets hadden om te laten reviewen. We hebben we het idee voorgesteld, waarbij we de feedback kregen om ons echt eerst te focussen op de flow van het plant swappen en om ons daarna te focussen om de andere mogelijke user stories. Deze feedback werd gegeven, omdat we vrij ambitieus zeiden wat we allemaal wouden maken.

### To do week 3

Volgende week gaan we echt een start maken met het coderen van de flow. Ik heb hierbij de taak van projectleider op mij genomen. Ik heb een aantal taken opgesteld die we volgende week gaan uitvoeren. We hebben de flow opgedeelt in een aantal taken, deze taken zijn:

- Uploader
- Resultaten
- Formulier component
- Kiezen van een plant

Ik heb zelf de taak van de uploader op mij genomen. De andere teamleden hebben een eigen component

## Week 3

In week hebben we de flow opgedeelt in taken en heb ik mij gefocused op het maken van het upload component. Het upload component bestaat uit de volgende onderdelen:

- Form
- Icon
- Title
- Text
- Input
- FileTile

Dit was de code van de uploader dat ik heb geschreven. Op het moment dat er een foto werd geupload, en de API heeft resultaten dan werden de resultaten getoond.

```javascript
"use client";

import { useState } from "react";
import Button from "../Button/Button";
import FileTile from "../FileTile/FileTile";
import Icon from "../Icon/Icon";
import Text from "../Text/Text";
import Title from "../Title/Title";
import styles from "./uploader.module.scss";
import Results from "../Results/Results";

const Uploader = () => {
  const [img, setImg] = useState(undefined);
  const [data, setData] = useState(undefined);

  function uploadImg(e) {
    setImg(e.target.files[0]);
  }

  function handleButton(e) {
    e.preventDefault();
    const baseUrl = "https://my-api.plantnet.org";
    const testImg =
      "https%3A%2F%2Fm.media-amazon.com%2Fimages%2FI%2F61vlqixclKL._AC_SX679_.jpg";
    const base = `${baseUrl}/v2/identify/all?images=${testImg}&include-related-images=true&no-reject=true&lang=nl&type=legacy&api-key=${apiKey}`;
    fetch(base)
      .then((res) => res.json())
      .then((data) => {
        setData(data);
      });
  }

  if (!data) {
    return (
      <>
        <form
          className={styles.uploader}
          onSubmit={(e) => {
            e.preventDefault();
          }}>
          <label className={styles.uploader__holder}>
            <Icon iconName="plus" />
            <Title title={"h3"}>Tik om een foto te uploaden of te maken</Title>
            <Text modifier={"small"}>Maximale bestandsgrootte: 10MB</Text>
            <input
              className={styles.uploader__file}
              type="file"
              accept="image/*"
              capture="camera"
              name="plant"
              onChange={uploadImg}
            />
          </label>

          <FileTile image={img} />
          <Button disabled={!img} next={handleButton}>
            Start Identificatie
          </Button>
        </form>
      </>
    );
  }

  return <Results data={data} />;
};

export default Uploader;
```

De FileTile bestond uit het volgende component:

```javascript
<section className={styles.filetile}>
  <img src="./testplant.jpg" className={styles.filetile__preview} />
  <Title title={"h4"} className={styles.filetile__name}>
    Screenshot_123.png
  </Title>
  <Text modifier={"small"} className={styles.filetile__size}>
    100 KB
  </Text>
</section>
```

> Zoals je kan zien zijn de huidige waardes nog hardcoded, dit is omdat de foto op dit moment nog niet geupload kon worden.

### Plant Identificeren

Het identificeren van de plant lukte voor zowel ons team als het andere team nog niet helemaal. Ik heb van het andere team mogen kijken hoe zij dit hebben opgelost en heb op basis van hen code een eigen implementatie gemaakt om de foto te uploaden en te identificeren. De front-end stuurd met de uploader een fetch naar de backend, de backend stuurt vervolgens een XMLHttpRequest (om de bestand uploadtijd te kunnen weergeven) naar de PlantNet API en stuurd de resultaten terug naar de front-end.

Dit is de functie XMLHttpRequest die ik heb geschreven:

```javascript
const fetchPlant = async () => {
  const formData = new FormData();
  formData.append("image", image);
  formData.append("lang", locale);

  const res = await fetch(API_URL, {
    method: "POST",
    body: formData,
  });
  const { data } = await res.json();

  setData(data);
};
```

> Zoals je kan zien wordt er ook een locale meegestuurd. Ik heb de website tweetalig (NL/EN) gemaakt, dit leg ik uit in de volgende sectie.

Het verzoek wordt opgevangen door de POST serverless function op de route `api/identify`. Deze functie stuurd vervolgens een XMLHttpRequest naar de PlantNet API en stuurd de resultaten terug naar de front-end. De foto wordt als butffer gestuurd, zodat de PlantNet API de foto kan verwerken.

```javascript
export const runtime = "nodejs";

// get image from post request without formidable next js
export async function POST(req, res) {
  const API_URL = `https://my-api.plantnet.org/v2/identify/all?include-related-images=true&no-reject=true&lang=${lang}&api-key=${API_KEY}`;
  const reqFormData = await req.formData();
  const file = reqFormData.get("image");
  const lang = reqFormData.get("lang");

  const stream = file.stream();

  const chunks = [];
  for await (const chunk of stream) {
    chunks.push(chunk);
  }
  const buffer = Buffer.concat(chunks);
  const form = new FormData();
  form.append("images", buffer, file.name);
  const response = await axios.post(API_URL, form, {
    headers: form.getHeaders(),
  });
  const data = response.data;
  return NextResponse.json({ data });
}
```

### Internationalization

Ik heb de website tweetalig gemaakt met behulp van de Next.js middleware. Ik heb een middleware script gemaakt dat checkt of de huidige pagina een locale heeft. Als dit niet het geval is wordt de gebruiker doorgestuurd naar de huidige pagina met de locale `nl`. Als de gebruiker op de website een andere locale selecteerd wordt de gebruiker doorgestuurd naar de huidige pagina met de nieuwe locale.

```javascript
import { NextResponse } from "next/server";
import { match } from "@formatjs/intl-localematcher";
import Negotiator from "negotiator";
import i18n from "../i18n-config.js";

let locales = ["en", "nl"];
let headers = { "accept-language": "nl-NL,nl;q=0.5" };
let languages = new Negotiator({ headers }).languages();
let defaultLocale = "nl";

function getLocale(request) {
  return match(languages, locales, defaultLocale);
}

export default function middleware(request) {
  // Check if there is any supported locale in the pathname
  const pathname = request.nextUrl.pathname;
  const pathnameIsMissingLocale = locales.every(
    (locale) => !pathname.startsWith(`/${locale}/`) && pathname !== `/${locale}`
  );

  // Redirect if there is no locale
  if (pathnameIsMissingLocale) {
    const locale = getLocale(request);

    // e.g. incoming request is /products
    // The new URL is now /en-US/products
    return NextResponse.redirect(
      new URL(`/${locale}/${pathname}`, request.url)
    );
  }
}

export const config = {
  matcher: [
    /*
     * Match all request paths except for the ones starting with:
     * - api (API routes)
     * - _next/static (static files)
     * - _next/image (image optimization files)
     * - favicon.ico (favicon file)
     */
    "/((?!api|_next/static|_next/image|favicon.ico|testplang.jpg).*)",
  ],
};
```

> Ik heb de locale `nl` als default locale ingesteld, omdat de opdrachtgever een Nederlandse organisatie is.

Naast de middleware maakt de app nu gebruik van een functie getDictionary functie. Deze functie kijkt naar de huidige params.lang, en geeft op basis hiervan een dictionary terug. Het dictionary is een JSON bestand met daarin de vertalingen van de website.

```javascript
import "server-only";

// We enumerate all dictionaries here for better linting and typescript support
// We also get the default import for cleaner types
const dictionaries = {
  en: () => import("./dictionaries/en.json").then((module) => module.default),
  nl: () => import("./dictionaries/nl.json").then((module) => module.default),
};

export const getDictionary = async (locale) => dictionaries[locale]();
```

> De params.lang is beschikbaar, omdat de pagina's van de website zijn genest in de map [lang], dit is een Next.js feature.

### Resultaten

Naast het maken van deze code heb ik ook de code van @Menno gerefactored. Ik heb de code opgeschoond en de code opgedeeld in meerdere componenten. Daarnaast was er een deel van het design nog niet helemaal correct verwerkt. Ik heb dit aangepast en de code opgeschoond.

Dit is de code waarin in de resultaten heb veranderd.

```javascript
{
  data.results.map((result, i) => (
    <Result
      key={i}
      plant={{
        plantName: result.species.commonNames[0],
        latinName: result.species.scientificNameWithoutAuthor,
        image: result.images[0].url.m,
        score: result.score,
        position: i + 1,
        topPosition: i <= 2,
        totalResults: data.results.length,
        recent: flowdata.flowData?.myplant?.gbif?.id === result?.gbif?.id,
      }}
      data={mydata}
      result={result}
    />
  ));
}
```

> Dit is de code waar de resultaten worden `gemapped` per result component.

```js
const Result = ({ data, plant, result }) => {
  const {
    flowdata: { setFlowData },
    dictionary,
  } = data;

  const resultStyle = () => {
    if (!plant.position && !plant.score) {
      return styles["result--overview"];
    }
    return styles["result--position"];
  };

  return (
    <>
      <section className={styles.result + " " + resultStyle()}>
        <Title className={styles.result__name} title={"h4"}>
          {plant.plantName}
        </Title>
        <Title className={styles.result__latin} title={"h5"}>
          {plant.latinName}
        </Title>

        {plant.image && (
          <Image
            className={styles.result__img}
            src={plant.image}
            alt="Foto van de plant"
            height={400}
            width={400}
            priority={true}
          />
        )}
        {result && (
          <Rank
            topPosition={plant.topPosition}
            rank={plant.position}
            score={Number.parseFloat(plant.score * 100).toFixed(1) + "%"}
          />
        )}

        {result && (
          <Button
            rotateIcon={90}
            className={styles.result__btn}
            modifier={["small", plant.recent ? "chosen" : "fresh"]}
            next={() => {
              setFlowData((prev) => {
                if (!plant.recent) {
                  return {
                    ...prev,
                    plantforms: {},
                    myplant: result,
                    step: prev.step + 1,
                  };
                }

                return {
                  ...prev,
                  myplant: result,
                  step: prev.step + 1,
                };
              });
            }}>
            {plant.recent
              ? dictionary.swapflow.myplant.button.recent
              : dictionary.swapflow.myplant.button.new}
          </Button>
        )}
      </section>
      {plant.position === 3 && (
        <CardLeftOver plant={plant} dictionary={dictionary} />
      )}
    </>
  );
};
```

> Zoals je kan zien is heb ik het result component opgesplitst in meerdere componenten. Dit heb ik gedaan om de code beter te structureren en om de code herbruikbaar te maken.

---

### Feedback week 3

#### Code review

Tijdens de code review met robert heb ik te horen gekregen dat de structuur van de code er goed uitziet, en dat ik goed gebruik maak van de Next.js features. Ik heb ook te horen gekregen dat ik de code beter kan structureren door de code op te delen in meerdere componenten.

### To do week 4

Deze week zijn we er achter gekomen dat sommige teamleden het nog lastig vinden om te werken met react forms. We hebben daarom de beslissing gemaakt, dat ik de taak van het formulier op mij neem en dat de rest van het team of verder gaat met de huidige taak en het design goed implementeren, of ze bezig gaan met de homepage. Naast het maken van het formulier ga ik ook bedenken hoe ik de verschillende onderdelen van de 'swapflow', aan elkaar kan koppelen.

## Week 4

Deze week heb ik gewerkt aan de formulieren, Ik heb hiervoor gebruik gemaakt van [Formik](https://formik.org), dit is een React library, waarmee je gemakkelijk formulieren kan maken. Ik heb de data van het formulier in een JSON bestand gezet, en op basis van het JSON bestand heb ik het formulier geprobeerd om generiek in te laden. Dit is een voorbeeld van het JSON bestand.

### Formulier

```JSON
{
"user": [
    {
      "title": "Persoonlijke gegevens",
      "fields": [
        {
          "name": "fullName",
          "title": "Volledige naam",
          "placeholder": "Volledige naam",
          "description": "Vul hier je volledige naam in",
          "type": "text"
        },
        {
          "name": "email",
          "title": "E-mailadres",
          "description": "Vul hier je e-mailadres in",
          "placeholder": "naam@voorbeeeld.nl",
          "type": "email"
        }
      ]
    },
    {
      "title": "Moment van ophalen",
      "fields": [
        {
          "name": "date",
          "title": "Ophaaldatum",
          "description": "Vul hier in wanneer je de plant wil komen ophalen",
          "placeholder": "Datum",
          "type": "date"
        },
        {
          "name": "time",
          "title": "Tijd",
          "description": "Vul hier het tijdstip in wanneer je de plant komt ophalen",
          "type": "time"
        }
      ]
    }
  ]
}

```

> Deze JSON data is een voorbeeld om het gebruikers informatie formulier te maken.

Vervolgens laad ik het formulier in op deze wijze.

```javascript
"use client";

import styles from "./Form.module.scss";
import Button from "../Button/Button";
import { Formik, Form } from "formik";
import { DisplayingErrorMessagesSchema, initialFormValues } from "./utils";
import formdata from "./formdata.json";
import FormTip from "../FormTip/FormTip";
import { useState } from "react";
import FormPart from "./FormPart";
import { FormIndicator } from "./FormIndicator";
import { FieldPartType } from "../FormField/FormField";

const SwapForm = ({ data, form, formData }) => {
  const { flowData, setFlowData } = data.flowdata;
  const currentForm = formData[form].map((form) => form.formSection[0]);
  const [currentStep, setCurrentStep] = useState(1);

  return (
    <Formik
      initialValues={initialFormValues(flowData, form, currentForm)}
      validationSchema={DisplayingErrorMessagesSchema(form, currentForm)}
      onSubmit={(values) => {
        setFlowData((prev) => {
          return {
            ...prev,
            [form]: values,
            step: prev.step + 1,
          };
        });
      }}>
      {(props) => {
        return (
          <Form className={styles.form}>
            <FormTip description={data.dictionary[form].tip_description} />

            {currentForm.map((step, i) => {
              return (
                <FormPart
                  step={i + 1}
                  title={step.title}
                  key={i}
                  props={props}
                  setCurrentStep={setCurrentStep}
                  currentStep={currentStep}>
                  <FormIndicator step={i + 1} currentStep={currentStep} />

                  {step.fields.map((field, i) => {
                    return (
                      <FieldPartType key={i} field={field} props={props} />
                    );
                  })}
                </FormPart>
              );
            })}

            <Button
              rotateIcon={90}
              type={"submit"}
              disabled={!props.isValid}
              children={
                flowData.step === 5 ? "Gegevens controleren" : "Volgende stap"
              }
              className={styles.form__button}
            />
          </Form>
        );
      }}
    </Formik>
  );
};

export default SwapForm;
```

> Vervolgens word er een fieldpart component gegenereerd, dit component zorgt ervoor dat de juiste formuliervelden worden ingeladen.

### SwapFlow

De swapflow is een flow die de gebruiker doorloopt, om een plant te kunnen ruilen of doneren. De swapflow bestaat uit een aantal stappen. Hoe de data tussen de pagina's word doorgegeven is doormiddel van een useState hook. Deze hook bevat de variablen `flowData` en `setFlowData`. De `flowData` bevat de data die de gebruiker heeft ingevuld in het formulier. De `setFlowData` is een functie die de `flowData` kan updaten. De `flowData` ziet er als volgt uit.

```javascript
const [flowData, setFlowData] = useState({
  apidata: {},
  chosenplant: {},
  myplant: {},
  plant: {},
  plantinfo: {},
  step: 1,
  swaptype: "swap",
  plantforms: {},
  userForms: {},
});
```

> De `flowData.step` zorgt ervoor dat de gebruiker door de flow heen kan navigeren.

De code van de SwapFlow ziet er als volgd uit.

```javascript
"use client";

import styles from "./swapflow.module.scss";
import { useEffect, useState } from "react";
import Switcher from "../Switcher/Switcher";
import Title from "../Title/Title";
import Text from "../Text/Text";
import SwapFlowReturn from "../SwapFlowReturn/SwapFlowReturn";
import Uploader from "../Uploader/Uploader";
import useStorage from "../../utils/useStorage";
import Results from "../Results/Results";
import Form from "../Forms/Form";
import SwapFlowCheck from "../SwapFlowCheck/SwapFlowCheck";
import SwapFlowInfo from "../SwapFlowInfo/SwapFlowInfo";

const flowdata = {
  apidata: {},
  chosenplant: {},
  myplant: {},
  plant: {},
  plantinfo: {},
  step: 1,
  swaptype: "swap",
  plantforms: {},
  userForms: {},
};

const SwapFlow = ({ formData, dictionary, locale }) => {
  const { getItem } = useStorage();
  const [flowData, setFlowData] = useState(flowdata);
  const totalSteps = flowData.swaptype === "donate" ? 6 : 7;

  useEffect(() => {
    setFlowData(
      getItem("flowData") ? JSON.parse(getItem("flowData")) : flowData
    );
  }, []);

  useEffect(() => {
    sessionStorage.setItem("flowData", JSON.stringify(flowData));
  }, [flowData]);

  return (
    <section className={styles.swapflow}>
      <SwapFlowReturn
        className={styles.swapflow__return}
        flowData={flowData}
        setFlowData={setFlowData}
        totalSteps={totalSteps}
      />
      <Title
        title={"h1"}
        className={styles.swapflow__title}
        modifier={"gentle-appear"}>
        {dictionary.swapflow.steptitle[`step-${flowData.step}`]}
      </Title>
      <Text className={styles.swapflow__surtitle} modifier={["italic"]}>
        {dictionary.swapflow.stepsurtitle[flowData.swaptype]}
      </Text>
      <Text modifier={"small"} className={styles.swapflow__description}>
        {dictionary.swapflow.stepdescription[`step-${flowData.step}`]}
      </Text>
      <FlowBase />
    </section>
  );

  function FlowBase() {
    const data = {
      flowdata: { flowData, setFlowData },
      locale,
      dictionary,
    };
    switch (flowData.step) {
      case 1:
        return <Uploader data={data} />; // identifier
      case 2:
        return (
          <Results
            mydata={data}
            flowdata={{ flowData, setFlowData }}
            data={flowData.apidata}
          />
        );
      case 3:
        return <SwapFlowInfo flowdata={{ flowData, setFlowData }} />;
      case 4:
        return <Form formData={formData} data={data} form={"plantforms"} />;
      case 5:
        if (flowData.swaptype === "donate")
          return <Form formData={formData} data={data} form={"userForms"} />;

        return (
          <Switcher
            formData={formData}
            flowdata={{ flowData, setFlowData }}
            data={data}
          />
        );
      case 6:
        if (flowData.swaptype === "donate")
          return <SwapFlowCheck data={data} />;

        return <Form formData={formData} data={data} form={"userForms"} />;
      default:
        return <SwapFlowCheck data={data} />;
    }
  }
};

export default SwapFlow;
```

> Zoals je kan zien worden de titels en descripties uit de dictionary gehaald op basis van de `flowData.step`.

### Feedback

#### Design review feedback.

Ik heb de feedback gekregen tijdens de design review dat het huidige formulier eigenlijk vrij saai was, het werd ook wel een belastingdienst formulier genoemt. We hebben vervolgens als team overlegd hoe we dit formulier kunnen opleuken. We hebben hiervoor een aantal ideeën bedacht.

##### Het design zag er eerst zo uit.

<img src="./docs/img/flow-1.png">

##### En dat hebben we veranderd naar.

<img src="./docs/img/flow-2.png">

### To do week 5

We naderen het einde van het project en moeten nog een aantal dingen doen. Met de feedback op het formulier hebben we besloten dat ik dat zou verwerken. @Danian en ik hebben in overleg een nieuw design voor gemaakt voor het formulier dat ik ga verwerken. Daarnaast wil ik ook het JSON bestand verwerken in Hygraph.

## Week 5

### Formulier

De laatste loodjes zijn begonnen. Ik heb deze week het formulier verwerkt in Hygraph. Daarnaast heb ik ook de feedback van de design review verwerkt. Ik heb het formulier wat speelser gemaakt, door elke `select` om te zetten in een rij met radio buttons. Deze radio buttons kon ik nu ok stylen met een icon. Daarnaast heb ik ook de site mascotte toegevoegd boven de formulier velden. Dit maakt het formulier wat speelser, en het zorgt er ook voor dat de gebruiker niet vergeet dat hij een plant aan het swappen is.

<!-- SS mascotte -->
<img src="./docs/img/mascotte.png" width="100">

### Hygraph

Ik heb deze week dus zowel de formulieren als de planten in hygraph gezet. Ik heb de formulieren in hygraph gezet, omdat we de formulieren ook online willen kunnen aanpassen. De planten moeten ook ergens opgeslagen worden, en omdat we al een database hebben voor de formulieren, hebben we besloten om de planten ook in hygraph te zetten. De planten werden eerst net als de formulieren ingeladen door een JSON bestand.

<img src="./docs/img/hygraph-form.png" width="49%">
<img src="./docs/img/hygraph-plant.png" width="49%">

Alle informatie staat dus nu, waardoor je gemakkelijk online de informatie kan wijzigen. Nu kan je ook in Hygraph later nog aanpassen of een veld van het formulier verplicht is of niet.

Ik heb de request naar Hygraph met graphQL op de volgende wijze gemaakt.

```js
import "server-only";
import { GraphQLClient, gql } from "graphql-request";

const client = new GraphQLClient(
  `https://api-eu-central-1-shared-euc1-02.hygraph.com/v2/${hygraphEndpoint}`
);

export async function getData(lang) {
  client.setHeader(`authorization`, `Bearer ${TOKEN}}`);
  const data = await client.request(query(lang));
  return data;
}

const query = (lang) => {
  return gql`
      query {
        plants(locales: ${lang}) {
          id
          plantName
          latinName
          origin
          maintenance
          waterInterval
          waterFrequency
          waterFrequencyCheckbox
          additionalWaterInfo
          fertilizer
          fertilizerDisclosure
          poisonous
          poisonousFor
          image
          reserved
          registered
        }
        userForms(locales: ${lang}) {
          formSection {
            ... on FormSection {
              title
              fields {
                title
                name
                type
                quantityType
                additionalInfo
                required
                description
                placeholder
                errorMessage
                optionList {
                    listOrientation
                    optionsHint {
                        ... on ListHint {
                            hintLow
                            hintHigh
                        }
                    }
                    optionName {
                      ... on Option {
                        name
                        key
                      }
                    }
                  }
  
                disclosure {
                    title
                    name
                    type
                    quantityType
                    additionalInfo
                    required
                    description
                    placeholder
                    errorMessage
                }
              }
            }
          }
        }
        plantforms(locales: ${lang}) {
          formSection {
            ... on FormSection {
              title
              fields {
                title
                name
                type
                quantityType
                additionalInfo
                required
                description
                placeholder
                errorMessage
                optionList {
                    listOrientation
                    optionsHint {
                        ... on ListHint {
                            hintLow
                            hintHigh
                        }
                    }
                    optionName {
                      ... on Option {
                        name
                        key
                      }
                    }
                  }
  
                disclosure {
                    title
                    name
                    type
                    quantityType
                    additionalInfo
                    required
                    description
                    placeholder
                    errorMessage
                }
              }
            }
          }
        }
      }
    `;
};
```

> Zoals je kan zien vraagt dit graphQL verzoek zowel de planten als de formulieren op. Dit is omdat de formulieren ook in Hygraph staan. Dit wordt gedaan, zodat alle informatie op één plek beschikbaar is.

### Detailpagina

Omdat de planten nu uit hygraph komen, kon ik op basis deze date de detail pagina invullen. Omdat @Danian al grotendeels de detailpagina heeft opgezet hoefde ik eigenlijk alleen nog maar de velden in te vullen en zorgen dat de pagina responsive is en er wordt gevalideerd of de pagina bestaat.

<img src="./docs/img/detailpage.png">

De code van de detailpagina ziet er als volgt uit.

```js
import DetailpageHeader from "../DetailpageHeader/DetailpageHeader";
import DetailpageArticle from "../DetailpageArticle/DetailpageArticle";

import Accordion from "../Accordion/Accordion";

import styles from "./detailpage.module.scss";
import WaterCount from "../WaterCount/WaterCount";
import Icon from "../Icon/Icon";

const Detailpage = ({ dictionary, plant, form }) => {
  const options = form
    .map((a) => a.formSection.map((b) => b.fields))
    .flat(2)
    .map((c) => (c.optionList !== null ? c : undefined))
    .filter((d) => d)
    .filter((e) => {
      if (
        e.name === "origin" ||
        e.name === "fertilizer" ||
        e.name === "poisonous"
      ) {
        return e;
      }
    });

  const fields = form.map((a) => a.formSection.map((b) => b.fields)).flat(2);

  return (
    <main className={styles.detailpage}>
      <DetailpageHeader plant={plant} />

      <section className={styles.detailpage__section}>
        {options.map((option, i) => {
          const content = option.optionList.optionName.find(
            (x) => x.key === plant[option.name]
          )?.name;

          const key = option.optionList.optionName.find(
            (x) => x.key === plant[option.name]
          )?.key;

          if (content) {
            return (
              <DetailpageArticle
                key={i}
                title={option.title}
                content={content}
                defaultValue={key}
                name={option.name}
              />
            );
          }
        })}

        {Object.keys(plant).map((key, i) => {
          const bannedValues = [
            "origin",
            "fertilizer",
            "poisonous",
            "id",
            "plantName",
            "image",
            "latinName",
            "reserved",
            "registered",
          ];

          if (bannedValues.includes(key)) return;

          if (plant[key] !== null) {
            const field = fields.find((x) => {
              return x.name === key;
            });
            if (field) {
              if (field.name === "maintenance")
                return (
                  <Accordion
                    key={i}
                    title={field.title}
                    content={
                      <Icon iconName={`groene-vinger-${plant[key]}`} />
                    }></Accordion>
                );

              if (field.name === "waterFrequency")
                return (
                  <Accordion
                    key={i}
                    title={field.title}
                    content={<WaterCount count={plant[key]} />}></Accordion>
                );

              if (field.name === "waterInterval") {
                return (
                  <Accordion
                    key={i}
                    title={field.title}
                    content={
                      fields
                        .find((x) => x.name === "waterInterval")
                        .optionList.optionName.find(
                          (x) => x.key === plant.waterInterval
                        ).name
                    }></Accordion>
                );
              }

              return (
                <Accordion
                  key={i}
                  title={field.title}
                  content={plant[key]}></Accordion>
              );
            }
          }
        })}
      </section>
    </main>
  );
};

export default Detailpage;
```

> Zoals je kunt zien zijn er een aantal waardes hardcoded. Omdat dit de laatste week van het project is heb ik geen tijd meer gehad om de code te refactoren. Dit is iets wat ik in de toekomst nog wel zou willen doen.

De detailpagina's worden ingeladen op basis van het ID in hygraph. Dit ID wordt meegegeven in de URL. Als dit ID niet bestaat dan krijgt de gebruiker de error pagina te zien. Ik heb deze error pagina gebasseerd op de homepage

<img src="./docs/img/error.png">

```js
import styles from "../../page.module.scss";
import Detailpage from "../../../../../components/Detailpage/Detailpage.js";
import Layout from "../../../../../components/Layout/Base.js";
import { getDictionary } from "../../../../../get-dictionary.js";
import { getData } from "../../../../../utils/getFormData.js";
import Hero from "../../../../../components/Hero/Hero.js";

export default async function Home({ params }) {
  const dictionary = await getDictionary(params.lang);
  const data = await getData(params.lang);
  const plant = data.plants.find((plant) => plant.id === params.id);

  return (
    <Layout dictionary={dictionary} locale={params.lang}>
      {plant && (
        <Detailpage
          dictionary={dictionary}
          plant={plant}
          form={data.plantforms}
        />
      )}
      {!plant && (
        <main className={styles.page}>
          <Hero
            dictionary={dictionary.errorplant}
            lang={params.lang}
            image={"/images/netwerk.png"}
            linkTo={`/${params.lang}/`}
          />
        </main>
      )}
    </Layout>
  );
}
```

> In de code hierboven kan je zien dat als er geen plant is gevonden de error hero wordt gerenderd. De content op de hero is afhankelijk van parameters, omdat dit component ook gebruikt wordt op de home pagina.

#### Hero component

Dit is de code van de het hero component

```js
import Image from "next/image";
import styles from "./hero.module.scss";
import Cta from "../Cta/Cta";
import Text from "../Text/Text";
import Link from "next/link";
import Title from "../Title/Title";

const Hero = ({ dictionary, lang, image, linkTo }) => {
  return (
    <section className={styles.hero}>
      <aside className={styles.hero__content}>
        <Title
          className={styles["hero__content-title"]}
          title={"h0"}
          modifier={"gentle-appear"}>
          {dictionary.title}
        </Title>
        <article className={styles["hero__content-intro"]}>
          <Text>{dictionary.intro}</Text>
          <Cta href={linkTo} role="primary" locale={lang}>
            {dictionary.button}
          </Cta>
        </article>
      </aside>

      <Image
        src={image}
        alt={"Hero image"}
        className={styles.hero__image}
        width={500}
        height={500}
      />

      {dictionary.sideNote && (
        <Link href="#overview-heading" className={styles.hero__sidenote}>
          {dictionary.sideNote} &#8594;
        </Link>
      )}
    </section>
  );
};

export default Hero;
```

> De sidenote is een boolean die aangeeft of de hero `Er is meer` text met animatie wordt getoond.

### Filters

Tot slot heb ik ook de filters voor @Dave afgemaakt. Hij had de filters ook op basis van een JSON bestand gemaakt, maar omdat de data nu komt uit hygraph heb ik de functie geschreven die de filters creeerd op basis van deze data. Daarnaast heb ik ook de homepagina gerefactored, zodat ik het hero component ook kon gebruiken op de error detailpagina.

<img src="./docs/img/filters.png">

Het belangrijkste dat ik heb gerefactored is de functie die de opties ophaalt uit hygraph en niet uit een JSON optie bestand

```js
const options = plants.formInfo
  .map((a) => a.formSection.map((b) => b.fields))
  .flat(2)
  .map((c) => (c.optionList !== null ? c : undefined))
  .filter((d) => d)
  .filter((e) => {
    if (
      e.name === "origin" ||
      e.name === "fertilizer" ||
      e.name === "poisonous"
    ) {
      return e;
    }
  });
```

> De options variabel is een array met alle opties die in de filters gebruikt worden. Deze opties worden opgehaald uit de formInfo van de planten. De formInfo is een array met alle formSections. De formSections zijn weer arrays met alle fields. De fields zijn de input velden van de planten. Als een field een optionList heeft dan wordt deze toegevoegd aan de options array. Als de optionList null is dan wordt deze niet toegevoegd aan de options array. Als de optionList niet null is dan wordt er gekeken of de optionList een van de drie filters is. Als dit zo is dan wordt de optionList toegevoegd aan de options array.

## Reflectie

Ik heb ontzettend veel nieuwe dingen geleerd tijdens de afgelopen vijf weken. Ik heb niet alleen geoefend met het coderen, maar ook met het ondersteunen van de groep. Ik heb geleerd om de groep te helpen met het oplossen van problemen, en ik heb geleerd om de groep te helpen met het maken van keuzes. We hadden als team wel een aantal keer een meningsverschil, maar we hebben dit altijd goed opgelost. Naast deze competenties heb ik ook leren werken met Next.js, ben ik beter geworden in React, heb ik geleerd hoe ik een website tweetalig kan maken, heb ik geleerd hoe ik met Formik supergemakkelijk een formulier kan maken, heb ik geleerd hoe ik een website continueus kan deployen met Vercel, heb ik geleerd hoe ik data kan zetten ophalen en verwerken met Hygraph en graphql en ben ik gewoon algemeen beter geworden in het schrijven van code.

### Wat ging er echt goed?

Ik vind dat de samenwerking tussen het team erg goed ging, misschien is de werkverdeling niet altijd even eerlijk geweest, maar ik vind dat we als team goed hebben samengewerkt. We hebben elkaar geholpen met het oplossen van problemen, en we hebben elkaar ook geholpen met het maken van keuzes. Ik vind dat we als team ook goed hebben gecommuniceerd, we hebben altijd goed overlegd en we hebben altijd goed naar elkaar geluisterd. Ik vind dat we als team ook goed hebben samengewerkt met de klant, we hebben goed geluisterd naar de klant en we hebben de klant ook goed op de hoogte gehouden van de voortgang.

### Wat ging er minder goed?

We hebben als team per persoon te grote taken op ons genomen, waardoor om verder te kunenn met het gehele project er vaak gewacht moest worden op elkaar. Ik merk dat ik zelf vrij snel werk en ik moest dus voor mijn gevoel af en toe pas op de plaats maken en wachten op mijn teamgenoten en hen code.

Aan het eind van het project reflecteer je systematisch op je werk en het proces.
Aan de hand van de vak-rubrics schrijf je welke vakken wel of niet aan bod zijn gekomen en waarom.
Zo krijg je een goed beeld van je eigen niveau, mogelijke aandachtspunten in techniek, interactie en/of aspecten van het design-proces waar je je nog op kan verbeteren.

### Toepassing op de vakken

#### Web App From Scratch

##### Data management - you understand how you can work with an external API using asynchronous code. You can retrieve data, manipulate and dynamically convert it to structured html

Ik heb meerder API verzoeken gedaan met `graphQL`, ik heb nog niet eerder met `graphQL` gewerkt. Als ik eerlijk ben vind ik het iets omslagtiger dan een normaal API verzoek, maar ik vind het wel fijn dat je precies kan aangeven welke data je wilt ophalen.

Naast de `graphQL` verzoeken heb ik ook verzoeken gedaan met `XMLHttpRequest` en `fetch`. Ik heb net als `graphQL` nog nooit eerder gewerkt met `XMLHttpRequest` en vind dat dit een iets krachtigere manier is om data op te halen dan `fetch`.

Ik heb zelfs ook een hele basic eigen REST API gemaakt dat gebruik wordt om de planten de identificeren (en voor in de toekomst ook planten toe te voegen aan hygraph).

#### Code structure - you write modular, consistent and efficient HTML, CSS and JavaScript code by applying structure and best practices. You manage state for the application and the UI

Naast het gebruiken van API heb ik ook geleerd hoe ik data kan verwerken en opslaan in de `sessionStorage`. Ik heb geleerd hoe ik data kan opslaan in de `sessionStorage` en hoe ik deze data kan ophalen en verwerken. Dit heeft ervoor gezorgt dat ik de states van de app kan bijhouden. Naast het opslaan van dat in de `sessionStorage` heb ik ook geoefent met de UI states, zo heb ik de error page gemaakt en heb ik de loading state gemaakt.

#### CSS to the Rescue

##### Meerdere contexten – media queries, media types, toegankelijkheid… Veel resultaat bereiken met weinig code. Zelfde resultaat bereiken met minder code.

Ik heb gebruik gemaakt van responsive variablen, zo kan ik met een responsive variable bijvoorbeeld de `--page-padding` aanpassen op basis van de breedte van het scherm.

```css
:root {
  --page-padding: 1rem;
  --header-height: 52px;
  --column-count: 1;
}

@media (min-width: 44em) {
  :root {
    --column-count: 2;
    --header-height: 70px;
    --page-padding: 2rem;
  }
}

@media (min-width: 70em) {
  :root {
    --page-padding: 6rem;
  }
}
```

Zoals je kan zien pas ik meerder variablen aan op basis van de breedte van het scherm. Deze variablen kan ik later gebruiken bij het stylen van elementen.

```scss
.page {
  padding: var(--page-padding);
}

.grid {
  display: grid;
  grid-template-columns: repeat(var(--column-count), minmax(0, 1fr));
}

.header {
  height: var(--header-height);
}
```

##### Een grote variëteit aan selectors passend inzetten en combineren

Dit zijn de belangrijkste selectors die ik heb gebruikt:

- `:not`
- `:has`
- `:is`
- `:checked`
- `:disabled`

Ik op bijvoorbeeld de volgende wijze

```scss
.disclosure {
  &[aria-collapsed="false"] &__title:is(summary) {
    margin-bottom: 1rem;
  }

  &[aria-collapsed="false"] &__title:not(input:checked) {
    margin-bottom: 1rem;
  }
}

.label:has(.checkbox:checked) {
  color: violet;
}

.button:disabled {
  opacity: 0.5;
  cursor: not-allowed;
}
```

> Note: ik heb deze styling geschreven ter illustratie van de selectors. Ik heb deze styling niet gebruikt in het project.

#### Browser technologies

##### Leerdoel: student begrijpt de principe van Feature detection en hoe je dit kan toepassen, Student kan voorbeeld noemen van hoe Feature Detection werkt en wat fallback is

Voor het vak browser technologies moetsen we ervoor zorgen dat ons applicatie zo goed mogelijk werkt op zo veel mogelijk apparaten en browsers. Dus de applicatie moet toegankelijkheid zijn voor iedereen. Ik heb hiervoor gebruik gemaakt van Feature Detection

Door gebruik te maken van feature detection kan je ervoor zorgen dat in dit geval de `sessionStorage`, mits aanwezig in het window object, wordt gebruikt. Het is dus een enhancement op de app als er `sessionStorage` aanwezig is.

```js
const useStorage = () => {
  const storageType = (type) => `${type ? "local" : "session"}Storage`;
  const isBrowser = (() => typeof window !== "undefined")();

  const getItem = (key, type) => {
    //   const storageType = `${type ?? 'session'}Storage`;
    return isBrowser ? window[storageType(type)][key] : "";
  };

  const setItem = (key, value, type) => {
    if (isBrowser) {
      window[storageType(type)].setItem(key, value);
      return true;
    }

    return false;
  };

  const removeItem = (key, type) => {
    window[storageType(type)].removeItem(key);
  };

  return {
    getItem,
    setItem,
    removeItem,
  };
};

export default useStorage;
```

> Zoals je kan zien kan de functie useStorage voor zowel de `localStorage` als de `sessionStorage` gebruikt worden.

Naast de useStorage heb ik ook een functie useXML gemaakt.

```js
const useXML = () => {
  const isBrowser = (() => typeof window !== "undefined")();

  const newXML = () => {
    return isBrowser && window?.XMLHttpRequest ? new XMLHttpRequest() : "";
  };

  return {
    newXML,
  };
};
export default useXML;
```

#### Progressive Web App

##### Serverside rendering, You’ve implemented serverside rendering and have articulated how it works and why you should want it.

Door gebruik te maken van Next.js wordt de geschreven React, door de server gerendered. Dit zorgt ervoor dat de tijd tussen de eerste request en het renderen van de pagina wordt verkort. Dit zorgt ervoor dat de website sneller aanvoelt. Dit is een van de voordelen van een Progressive Web App.

<img src="./docs/img/serverflow.png">

#### Human Centred Design

##### Design Principles - Student laat zien hoe de Exclusive Design Principles zijn toegepast in het ontwerp. De principes study situation, prioritise identity, ignore conventions en add nonsense zijn goed uitgelegd. Aan de hand van de principes wordt duidelijk gemaakt hoe deze hebben bijgedragen aan het verbeteren van het ontwerp.

In het speciaal het principe add nonsense. We kregen als team de design feedback dat het formulier vrij saai was. We hebben hiervoor nonsense toegevoegd om het formulier interessanter te maken. Dit hebben we bijvoorbeeld gedaan door de rups te tonen boven de invul velden.

<img src="./docs/img/mascotte.png" alt="rups for fun" width="200">

Daarnaast ook een rups emoji gebruikt als marker van de filters.

<img src="./docs/img/filters.png" alt="rups for fun">

### Een blije klant

Naast het ontwikkelen van een applicatie voor de klant, is het natuurlijk ook van belang dat de klant er blij mee is. Ik weet zeker dat dit is gelukt. We hebben meerdere feedback rondes gehad, waaruit bleek dat elke iteratie een stap in de juiste richting was. Met het eindresultaat is de klant dan ook erg blij. We hebben met twee teams hebben gewerkt aan dezelfde opdracht (maar wel een eigen versie), de opdrachtgever was met beide versies erg blij en zei daarna nog dat ze beide versies zo leuk vond dat het nog maar de vraag is welke wordt geimplementeerd. Dit is natuurlijk een groot compliment.
