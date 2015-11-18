---
title       : Vancomycin Dose Adaption in Renal Insufficiency
subtitle    : Developing Data Products - Peer Assessment - Johns Hopkins at Coursera
author      : iNocebo - Dominik Staempfli
job         : devdataprod-034, November 2015
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz, interactive]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is Vancomycin? 

- Vancomycin is a glycopeptide antibiotic used for severe bacterial infections 
- It is known for being a last line treatment of Methicillin-resistant Staphylococcus aureus - also known as MRSA 

### Vancomycin dosing regimens need careful evaluation: 
- Dosing should be high enough to prevent the further spread of resistant bacteria 
- Dosing should be low enough to prevent adverse drug reactions such as kidney damage, hearing impairment or rash 

---

## Why do we need an application for dosing Vancomycin 

- Vancomycin elimination (read: "pushing the drug out of the body") is heavily dependant on renal function 
- Estimating the renal function of the patient is necessary to dose Vancomycin correctly and individually 
- The renal function of a patient can be estimated when *sex*, *age*, *body weight* and *plasma Creatinine concentrations* are known
- Concentrations present in the patient's body can be estimated when renal function, dose and dosing intervals are known
 
- **An application performing quick and easy calculations will promote safer and more efficient Vancomycin use and may promote drug knowledge in a playful environment.**

--- &interactive

## Calculate your own distribution volume of Vancomycin right now!

<div class="row-fluid">
  <div class="col-sm-4">
    <form class="well">
      <div class="form-group shiny-input-container">
        <label for="bw">Enter your body weight in kg:</label>
        <input id="bw" type="number" class="form-control" value="70" min="5" max="140" step="1"/>
      </div>
    </form>
  </div>
  <div class="col-sm-8">
    <p>Vancomycin would dilute itself in the following distribution volume [L] within your body: </p>
    <pre id="odistr" class="shiny-text-output"></pre>
  </div>
</div>

--- &radio

## The quiz to exit 

Who do you think would benefit from a Vancomycin dosing regimen calculator?

1. A lawyer
2. _A physician_
3. _A pharmacist_
4. A astronaut

*** .hint

Vancomycin is a dangerous drug, it should be used by healthcare professionals

*** .explanation
Physicians prescribe the dosing regimens but may be adviced by pharmacists while choosing it. Thank you for taking a look into my assigment!
