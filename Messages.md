# Auto Messages and Replies

## Table of content

- [Auto Messages and Replies](#auto-messages-and-replies)
  - [Table of content](#table-of-content)
  - [Welcome Message](#welcome-message)
  - [Rules](#rules)

## Welcome Message

Messages send every time some joins the server. 

![](Images/Preview%20Images/Welcome_Message_pre.png)

<details>
<summary>Code</summary>

```json
{
  "content": null,
  "embeds": [
    {
      "color": 16741141,
      "image": {
        "url": "https://i.imgur.com/b32PBsX.png"
      }
    },
    {
      "description": "<@USER_ID> Wir hoffen, du hattest eine angenehme Reise und wir wünschen dir einen schönen Aufenthalt auf dem `Moni Heichou` Discord™ Server.",
      "color": 16741141
    },
    {
      "description": "Wir empfehlen dir zunächst die folgenden Channels durchzulesen: \n\n- <#CHANNEL_ID> (Server Information)\n- <#CHANNEL_ID> (Regeln)\n- <#CHANNEL_ID> (Ankündigungen)\n- <#CHANNEL_ID> (Rollen)\n\nSobald du den Regeln zugestimmt hast, erhältst du zum gesamten Server Zugriff.",
      "color": 16741141
    }
  ],
  "attachments": []
}

```
</details>

## Rules

Display of the rules in `#regeln`

![](Images/Preview%20Images/Rules_Messages_pre.png)

<details>
<summary>Code</summary>

```json
{
  "content": null,
  "embeds": [
    {
      "color": 16741141,
      "image": {
        "url": "https://github.com/OutofSpaceUwU/Dreamy-Code/blob/main/Images/Embeded%20Images/First_Paragraph.png?raw=true"
      }
    },
    {
      "title": "–––––––––––––––––––––––––",
      "description": "**1. Das Serverteam ist berechtigt, nach eigenem Ermessen zu urteilen. Dein Zugang kann jederzeit und aus jedem Grund entfernt werden\n\n2. Es ist verboten, den Server mit einem zweiten Account zu betreten\n\n3. Sobald du auf den grünen Hacken unter der Nachricht auf dem Discord-Server klickst und Zugang zum Server erhältst, akzeptierst du die Regeln\n\n4. Änderungen an den Regeln können jederzeit vorgenommen werden und treten sofort in Kraft\n\n5. Jeder, der gebannt oder stumm geschaltet wird, hat das Recht, ein Formular auszufüllen und eine Aufhebung der Sperre oder Stummschaltung zu beantragen\n\n6. Die allgemeinen Discord™ Community Guidelines (https://discord.com/guidelines) und Terms of Service (https://discord.com/terms) gelten natürlich auch für diesen Server**",
      "color": 16741141,
      "footer": {
        "text": "Zuletzt geändert"
      },
      "timestamp": "2022-08-07T02:40:00.000Z"
    },
    {
      "color": 16741141,
      "image": {
        "url": "https://github.com/OutofSpaceUwU/Dreamy-Code/blob/main/Images/Embeded%20Images/Second_Paragraph.png?raw=true"
      }
    },
    {
      "title": "–––––––––––––––––––––––––",
      "description": "**1. Behandel andere Benutzer mit Respekt**\n> a. Besonders das Staff-Team\n\n**2. Versuche, jede Art von unnötigem Drama zu vermeiden\n\n3. Halte toxisches Verhalten und Fluchen im Rahmen\n\n4. Vermeide unnötige Pings\n\n5. Die Verbreitung von extremistischem Gedankengut in jeglicher Form ist verboten. Dies schließt politische und ideologische Einstellungen und die Verbreitung von irreführenden Informationen ein.\n\n6. Hassreden sind inakzeptabel und werden nicht geduldet\n\n7. Drohe nicht mit Gewaltanwendung\n\n8. Verbreite keine schädlichen Computerprogramme oder betreibe Hacking-Angriffe**\n> Darunter zählen folgede Aktivitäten/Programme:\n> - Viren, Malware und andere schädliche Codes/Programme\n> - Fishing, Hacking und DDoS-Angriffe\n\n**9.  Die einzigen beiden Sprachen, die auf dem Server erlaubt sind, sind Deutsch und Englisch**",
      "color": 16741141,
      "footer": {
        "text": "Zuletzt geändert"
      },
      "timestamp": "2022-07-04T09:13:00.000Z"
    },
    {
      "color": 16741141,
      "image": {
        "url": "https://github.com/OutofSpaceUwU/Dreamy-Code/blob/main/Images/Embeded%20Images/Third_Paragraph.png?raw=true"
      }
    },
    {
      "title": "–––––––––––––––––––––––––",
      "description": "**1. Benutze Caplocks, Emotes etc. nicht im Übermaß**\n> 10 Zeichen auf einmal sind erlaubt\n\n**2. Spamme nicht**\n> a. Das <@&983819709185142784>-Team ist davon unter gegebenen Umständen ausgeschlossen\n\n**3. Benutze die `spoiler`-Option, wenn es angebracht ist\n\n4. Verwende die Channel themenspezifisch**\n> a. Verwende die neue VC-Text-Funktion, falls sich das Thema auf einen spezifischen Voice Chat bezieht\n> b. Benutze <#983818350595551385> für sämtliche <@&983819748196376607>-commands\n\n**5. Verbotene Inhalte**\n> a. NSFW (außer die gekenzeichneten 18+ Kanäle)\n> b. Sexualisierung von Minderjährigen\n> c. Visualisierung von Gewaltanwendung oder Tierquälerei\n> d. Eigenwerbung, Bewerbung von Produkten, Werbung für andere Discord™-Server\n> e. Förderung von illegalem Material und/oder Ermutigung zu illegalen Aktivitäten",
      "color": 16741141,
      "footer": {
        "text": "Zuletzt geändert"
      },
      "timestamp": "2022-07-04T09:38:00.000Z"
    },
    {
      "color": 16741141,
      "image": {
        "url": "https://github.com/OutofSpaceUwU/Dreamy-Code/blob/main/Images/Embeded%20Images/Fourth_Paragraph.png?raw=true"
      }
    },
    {
      "title": "–––––––––––––––––––––––––",
      "description": "**1. Keine Art von NSFW-Content in den Sprachkanälen\n\n2. Kein Ear-Rape\n\n3. Kein VC-Hopping\n\n4. Benutze <#983818342731251784> vorwiegend für Musik**",
      "color": 16741141,
      "footer": {
        "text": "Zuletzt geändert"
      },
      "timestamp": "2022-07-04T09:48:00.000Z"
    }
  ],
  "username": "Dreamy Code",
  "avatar_url": "https://github.com/OutofSpaceUwU/Dreamy-Code/blob/main/Design%20Assets/binary-code.png?raw=true",
  "attachments": []
}
```
</details>
