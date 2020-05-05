# Chat-Security-Advance

Live Site (https://www.secadv.datavader.be/).

## Installation 
``` bash
npm install
```
``` bash
npm run serve
```
# ToDo 

### Level C requirements: 

 - [x]  Standalone applicatie (enkel local op uw eigen laptop) voor minstens 2 gebruikers, Alice en Bob
 - [x]  Er moet geen inlog zijn. App mag opgestart worden als zijnde voor gebruiker A. Daarna sluiten. Terug openen als zijnde gebruiker B.
 - [x]  Key generation en (local) storage voor symmetric / asymmetric crypto voor iedere gebruiker
 - [x]  Het moet mogelijk zijn om zowel tekst, als een file, naar B te sturen, via hybrid principe 
 - [x]  Er moet een check gebeuren na ontvangst van hybrid principes (signature en hash check)

### Level B requirements: 

- [x]  Client / server applicatie (moet geen online server zijn, maar mag), aka front- en back-end. Liefst web front-end, maar geen vereiste (mag bv ook mobile of iets anders zijn)
- [x]  ‘new user’ en inlog module (en dus ook user authentication via bv password)
- [x]  OWASP Pro-Active Controls: definieer specifieke security requirements uit de OWASP ASVS standards waaraan jullie project zal moeten voldoen (pro-active, dus voor er mee te starten), en highlight bij de analyse fase die delen van jullie applicatie waar expliciet aandacht zal worden aan besteed volgens de top-10 pro-active controls. Highlight bij jullie verdediging dan ook specifieke delen die aangepast waren ten gevolge van deze guidelines.
 	* Note: deze standards en guidelines zijn het meest toepasbaar op web-based front-ends, maar vele van deze issues gelden ook voor andere soorten front-ends

### Level A requirements:

- [x]  Code quality is ook voor security doeleinden belangrijk. Bugs en flaws kunnen nefast zijn voor secure code. Buiten de OWASP Pro-Active guidelines, zijn er ook tools die automatisch kunnen scannen op coding best practices, code smell detection, (unit test coverage), maar ook automatische checks doen op vulnerabilities, o.a. gebaseerd op de OWASP guidelines. De meest gekende tool hiervoor is Sonarqube. Run je code base eens op sonarqube, en analyseer de resultaten.

### Level A+ requirements:

- [x]  Sky is the limit… 
- [ ] Verschillende manieren van authentication: (Google) 2FA module, fingerprint login of andere biometrics, Belgische eID login/certificaten…
- [x] Online applicatie over https, met bv Let’s Encrypt certificaten
- [ ] Toevoeging van steganografie om encrypted file te verbergen in bv image om die door te sturen
- [ ] JWT tokens, OAuth,…

