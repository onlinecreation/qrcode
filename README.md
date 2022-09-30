<h1 align="center"><img alt="QRBTF" src=".github/qrbtf-logo.svg" height="75"></h1>

<p align="center">
    URL: <a href="https://qrcode.onlinecreation.pro" rel="noopener noreferrer" target="_blank">qrcode.onlinecreation.pro</a><br />
    QRBTF est une application web simple pour embellir votre code QR.
</p>

<p align="center">
    <img src="public/img/QRcodes.jpg">
</p>

## Caractéristiques

* Divers styles de codes QR graphiques
* Conception paramétrée
* Aucun traitement serveur requis
* Prend en charge les téléchargements SVG

### Installation

``` bash
git clone https://github.com/ciaochaos/qrbtf.git
cd qrbtf
npm install
npm start
```

### Utilisation

1. Ouvrez [qrcode.onlinecreation.pro] (https://qrcode.onlinecreation.pro).
2. Saisissez une URL ou un texte.
3. Sélectionnez un style.
4. Ajustez les paramètres.
5. Téléchargez votre QRcode au format `JPG` ou `SVG`.

## React Component (react-qrbtf)

Voir [CPunisher / react-qrbtf](https://github.com/cpunisher/react-qrbtf) pour plus d'informations.

``` bash
npm install react-qrbtf --save
```

### Inclure le composant

```js
import React from 'react'
import { QRNormal } from 'react-qrbtf'

class Component extends React.Component {

    render() {
        return (
            <QRNormal
                value="react-qrbtf"
                className="my-qrcode"
                styles={{ svg: {width: "200px"} }}
                type="round"
                size={50}
                opacity={80}
                posType="planet"
                otherColor="#33CCCC"
                posColor="#009999"
            />
        )
    }
}
```

## Auteur

* [ciaochaos](https://github.com/ciaochaos)
* [CPunisher](https://github.com/CPunisher)
* Traduit de l'anglais et du chinois par [OnlineCreation](https://www.onlinecreation.pro)

## Donation

Voir [le dépot père](https://github.com/ciaochaos/qrbtf)

## Dépendance

* [davidshimjs / qrcode](https://github.com/davidshimjs/qrcodejs)
* [cozmo / jsQR](https://github.com/cozmo/jsQR)

## Licence

[GPLv3](LICENSE)
