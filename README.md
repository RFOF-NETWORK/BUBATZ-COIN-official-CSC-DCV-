# BUBATZ COIN official (CSC/DCV)
### Projektstruktur und Dateien für Bubatz Coin Official (CSC-DCV)

Das Repository für den Bubatz Coin Official (CSC-DCV) beinhaltet die folgenden Verzeichnisse und Dateien:

```plaintext
BubatzCoin/
├── contracts/
│   ├── BubatzCoin.sol
│   ├── BBC_Training.sol
│   ├── BubatzManager.sol
│   ├── CTC.sol
│   └── CTC_Training.sol
├── migrations/
│   └── 1_deploy_contracts.js
├── test/
│   ├── BubatzCoin.test.js
│   ├── BBC_Training.test.js
│   ├── CTC_Training.test.js
├── scripts/
│   └── BubatzManager.js
├── .gitignore
├── README.md
├── truffle-config.js
├── package.json
└── $BBC_Token_Code.py.fc
```

### Dateien im Detail

- **contracts/**:
  - **BubatzCoin.sol**: Der Haupt-Smart-Contract für den Bubatz Coin.
  - **BBC_Training.sol**: Smart Contract für den BBC Training Token.
  - **BubatzManager.sol**: Der Manager-Smart-Contract, der das Ökosystem steuert.
  - **CTC.sol**: LP-Token-Smart-Contract für den Cannabis Technik Coin.
  - **CTC_Training.sol**: Smart Contract für den CTC Training Token.

- **migrations/**:
  - **1_deploy_contracts.js**: Deployment-Skript für die Smart Contracts.

- **test/**:
  - **BubatzCoin.test.js**: Tests für den BubatzCoin Smart Contract.
  - **BBC_Training.test.js**: Tests für den BBC Training Smart Contract.
  - **CTC_Training.test.js**: Tests für den CTC Training Smart Contract.

- **scripts/**:
  - **BubatzManager.js**: Skript zur Interaktion mit dem Bubatz Manager Smart Contract.

- **.gitignore**: Dateimuster, die von Git ignoriert werden sollen.
- **README.md**: Dokumentation des Projekts.
- **truffle-config.js**: Konfiguration für das Truffle Framework.
- **package.json**: Konfigurationsdatei für npm.
- **$BBC_Token_Code.py.fc**: Python-Datei für zusätzliche Funktionalität.

### Smart Contract Code

**BBC_Training.sol**
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract BBC_Training {
    // Contract code for BBC Training Token
}
```

**CTC_Training.sol**
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract CTC_Training {
    // Contract code for CTC Training Token
}
```

### Test-Skripte

**BBC_Training.test.js**
```javascript
const BBC_Training = artifacts.require("BBC_Training");

contract("BBC_Training", accounts => {
    it("should deploy the BBC_Training contract", async () => {
        const instance = await BBC_Training.deployed();
        assert(instance.address !== '');
    });

    // Weitere Tests hier hinzufügen
});
```

**CTC_Training.test.js**
```javascript
const CTC_Training = artifacts.require("CTC_Training");

contract("CTC_Training", accounts => {
    it("should deploy the CTC_Training contract", async () => {
        const instance = await CTC_Training.deployed();
        assert(instance.address !== '');
    });

    // Weitere Tests hier hinzufügen
});
```

### NPM Paketinstallation

Um das Projekt zu installieren und die notwendigen Pakete hinzuzufügen, verwende die folgenden Befehle:

```bash
npm install @RFOF-NETWORK
```

Dieser Befehl installiert das benötigte Paket von @RFOF-NETWORK.

# Lizenz
 * BSL 1.1 for non-commercial use
Business Source License 1.1
Lizenzinformationen
Dieses Projekt ist unter der Business Source License 1.1 (BSL 1.1) für nicht-kommerzielle Nutzung lizenziert.

Lizenzbedingungen
Die folgenden Bedingungen gelten für die Nutzung dieser Software unter der BSL 1.1:

Nutzungseinschränkung: Die lizenzierte Software darf nur für nicht-kommerzielle Zwecke verwendet werden2.

Änderungsdatum: Nach einem bestimmten Datum (bekannt als Änderungsdatum) erlöschen die Nutzungseinschränkungen und die Software wird automatisch unter einer Open-Source-Lizenz bereitgestellt, die in der Lizenzbeschreibung angegeben ist2.

Änderungslizenz: Nach dem Änderungsdatum wird die Software unter den Bedingungen der angegebenen Open-Source-Lizenz bereitgestellt2.

Nicht-kommerzielle Nutzung: Nicht-kommerzielle Nutzung umfasst, aber ist nicht auf, persönliche Projekte, Bildungszwecke und Forschung, die nicht darauf abzielen, kommerzielle Ergebnisse zu erzielen2.

Zuordnung: Jede Verwendung der Software muss die ursprünglichen Autoren entsprechend der Lizenzangabe zitieren2.

Haftungsausschluss
Die Software wird "so wie sie ist" bereitgestellt, ohne jegliche Garantie, weder ausdrücklich noch stillschweigend, einschließlich, aber nicht beschränkt auf die Garantien der Handelsfähigkeit, Eignung für einen bestimmten Zweck und Nichtverletzung. In keinem Fall haften die Autoren oder Rechteinhaber für Ansprüche, Schäden oder andere Haftungen, die aus, aus oder im Zusammenhang mit der Software oder deren Verwendung oder anderen Geschäftsbeziehungen entstehen.

Vollständige Lizenzbeschreibung
Die vollständige Lizenzbeschreibung der Business Source License 1.1 kann hier gefunden werden.
