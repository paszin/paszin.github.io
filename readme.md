
MY Website

Design inspired by [sindresorhus.com](https://sindresorhus.com)


# Projects Backlog


- **Resume Analysis** (#sap #angular #machinelearning)
- **ChargeIT** (#sap #python #backend #flask)
- **Soundcloud Mashup** (#music #angular)
- **3D-Printing** 
+ Gostly
+ LED Matrix
- **Kitchenflow?**
- **SORMAS-N** 
 + Video
 + Project Page
- **SharkLED** 
  + TODO: Video
- Earth Care (#hackathon #nasa)
- pizza pizza (#hackathon #traitify)
- Goalden (#hackathon #sap #soccer)


Soundcloud Mashup
Extend functionality of Soundcloud
Scope: personal project in my freetime, still under development

Resume Analysis
Automate the process of analyzing resumes and compare and match them to job openings
Scope: Project at Innovation Center SAP

ChargeIT
Improve the EV-charging experience at the SAP Campus in Palo Alto
Scope: Project at Innovation Center SAP

SORMAS-N
Digitize and improve the process of Contact Tracing in Nigeria in order to stopp the spreading of Ebola
Scope: Bachelor´s Project at the Hasso-Plattner-Institute



SharkLED
Control LED-Stripes and make cool light effects
Scope: Home Project


Dreams2Plan
stop dreaming and see the world
Scope: Travel Hackathon San Francisco 2015


easySpinUp
Continous Integration Platform for netapp
Scope: DeveloperWeek Hackathon San Francisco 2016





Colors
#03253B,#0F3550,#1E4564,#2F5677,#42688A,#55799C,#6A8BAD,#819EBD,#98B1CC,#B1C4DA,#CAD7E7,#E5EBF2



# Dev notes


## Generate the minified CSS

Comment out the `<link>` in `index.html` and uncomment the commented ones.

```
$ npm install --global uncss
```

```
$ uncss index.html --ignore=".nav-menu.is-active" >! main.min.css
```

