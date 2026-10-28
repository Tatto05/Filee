<p align="center">
  <a href="https://filee.sh"><img src="docs/media/banner-en.jpg" alt="Filee: Trascina. Rilascia. Convertito." width="100%"></a>
</p>

<p align="center">
  <b>Un convertitore di file gratuito e open source che usi trascinando.</b><br>
  Tieni premuto un tasto (<kbd>Ctrl</kbd>, <kbd>Option</kbd> su macOS), trascina i file e rilasciali su un formato nella donut che si apre in corrispondenza del cursore.
</p>

<p align="center">
  <a href="https://filee.sh"><b>Sito web</b></a> ·
  <a href="https://github.com/KnifeLemon/Filee/releases/latest"><b>Download</b></a> ·
  <a href="https://www.linkedin.com/company/filee-sh/"><b>LinkedIn</b></a> ·
  <a href="#install">Installazione</a> ·
  <a href="#command-line">Riga di comando</a> ·
  <a href="#development">Sviluppo</a>
</p>

<p align="center">
  <a href="https://github.com/KnifeLemon/Filee/actions/workflows/ci.yml"><img src="https://github.com/KnifeLemon/Filee/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://github.com/KnifeLemon/Filee/releases/latest"><img src="https://img.shields.io/github/v/release/KnifeLemon/Filee?color=7F77DD&label=release" alt="Ultima release"></a>
  <a href="https://github.com/KnifeLemon/Filee/releases"><img src="https://img.shields.io/github/downloads/KnifeLemon/Filee/total?color=1D9E75" alt="Download"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-3C3489" alt="Windows 10 | 11">
  <img src="https://img.shields.io/badge/Linux-x64%20%7C%20ARM64-3C3489" alt="Linux x64 | ARM64">
  <img src="https://img.shields.io/badge/macOS-preview-534AB7" alt="macOS preview">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-6A62C9" alt="Licenza MIT"></a>
</p>

<p align="center">
  <a href="https://trendshift.io/repositories/276987"><img src="https://trendshift.io/api/badge/trendshift/repositories/276987/weekly?language=C%23&v=2" alt="Filee: #1 repository C# della settimana su Trendshift" width="250" height="55"></a>
  <a href="https://trendshift.io/repositories/276987"><img src="https://trendshift.io/api/badge/trendshift/repositories/276987/daily?language=C%23&v=2" alt="Filee: #1 repository C# del giorno su Trendshift" width="250" height="55"></a>
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.es.md">Español</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a> ·
  <a href="README.zh-CN.md">简体中文</a> ·
  <a href="README.zh-TW.md">繁體中文</a> ·
  <a href="README.pl.md">Polski</a> ·
  <a href="README.hi.md">हिन्दी</a> ·
  <a href="README.ru.md">Русский</a> ·
  <a href="README.ar.md">العربية</a> ·
  <a href="README.pt-BR.md">Português (Brasil)</a> ·
  <a href="README.pt-PT.md">Português (Portugal)</a> ·
  <a href="README.fr.md">Français</a> ·
  <a href="README.th.md">ไทย</a> ·
  <a href="README.tr.md">Türkçe</a> ·
  <a href="README.it.md">Italiano</a>
</p>

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Proprio sotto il tuo cursore</b><br>
      Nessuna finestra dell'app da aprire.
      I formati appaiono dove ti trovi già, solo quelli compatibili con i file che trascini.
    </td>
    <td width="33%" valign="top">
      <b>268 formati, nessun altro software</b><br>
      Immagini, PDF, Word, Excel, PowerPoint, HWP, e-book, archivi, font, CAD, modelli 3D e dati geospaziali funzionano senza Office, Hancom Office o LibreOffice.
    </td>
    <td width="33%" valign="top">
      <b>Resta sul tuo computer</b><br>
      Niente viene caricato online.
      Filee funziona offline e salva il risultato accanto all'originale.
    </td>
  </tr>
</table>

## Guardalo in azione

<p align="center">
  <a href="https://filee.sh"><img src="docs/media/demo-en.webp" alt="Trascina trip.jpg tenendo premuto Ctrl: si apre una donut di formati al cursore, il file viene rilasciato su PNG, un anello di avanzamento si completa e appare trip.png" width="820"></a><br>
  <sub>Guarda il video di 27 secondi e prova la demo interattiva su <a href="https://filee.sh">filee.sh</a></sub>
</p>

## Installazione

Scarica da [Releases](https://github.com/KnifeLemon/Filee/releases/latest).

<a href="https://apps.microsoft.com/detail/XPDCN05L89WS0C?referrer=appbadge&cid=github&mode=full"><img src="https://get.microsoft.com/images/en-us%20dark.svg" alt="Microsoft Store" width="200"></a>

- **Windows 10/11**: esegui `Filee-<versione>-win-Setup.exe`, oppure estrai `win-Portable.zip` ed esegui `Filee.exe`.
  - L'installer (Setup) è quello proprietario di Filee, nelle lingue di Filee, e non richiede altro sul PC.
  - Può aggiungere il menu contestuale di Esplora file, l'avvio all'accesso, il comando `filee` e i motori opzionali.
  - Le installazioni silenziose accettano i parametri di Inno Setup (`/VERYSILENT /SUPPRESSMSGBOXES`).
- **macOS 13+** (anteprima): estrai il pacchetto `osx-arm64` o `osx-x64` ed esegui `./install.sh`.
  - Oppure apri il file `.dmg` e trascina Filee in Applicazioni (il comando `filee` viene fornito con `install.sh`).
  - La build non è ancora notarizzata, quindi autorizza il primo avvio in Impostazioni di sistema → Privacy e sicurezza → **Apri comunque**.
- **Linux x64/ARM64** (Ubuntu 22.04+): estrai il pacchetto ed esegui `./install.sh` (senza permessi di root, richiede Python 3).
  - Le gesture di trascinamento richiedono X11.
    Su Wayland, usa la zona di rilascio (drop zone) e il menu del tasto destro del gestore file.

Filee mostra le nuove release nel suo menu e si aggiorna automaticamente, mantenendo le tue impostazioni e i tuoi motori.
Dopo un aggiornamento, alcune diapositive mostrano le novità.

**Windows: Filee non si avvia (nessuna finestra, nessun errore)?**
Questo accade su Windows 10 non aggiornato da molto tempo, su un PC il cui processore supporta la protezione dello stack applicata dall'hardware (CET).
Windows attiva tale protezione ma manca di un componente necessario a .NET, quindi Filee e l'installer si interrompono immediatamente.

- **Consigliato:** installa gli aggiornamenti di Windows disponibili (l'ultimo aggiornamento cumulativo).
- **Se non è possibile aggiornare:** disattivare la protezione solo per Filee di solito funziona.
  Esegui questo comando in PowerShell come amministratore:

```powershell
Set-ProcessMitigation -Name Filee.exe -Disable UserShadowStack
Set-ProcessMitigation -Name filee-cli.exe -Disable UserShadowStack
