<!-- Introduction -->
# Moni Heichou Discord Server Github Page

This repository is a summary of the changes commited to the [Moni Heichou Discord Server](https://discord.gg/U2MSjuZAT7 "Invite Link") and a guide for the users and the moderation team.

<details>
<summary>Cheers</summary>

```
      _                        
     | |                       
  ___| |__   ___  ___ _ __ ___ 
 / __| '_ \ / _ \/ _ \ '__/ __|
| (__| | | |  __/  __/ |  \__ \
 \___|_| |_|\___|\___|_|  |___/
``` 
</details>

---

<!-- Content  -->
## Table of content
<details>

- [Moni Heichou Discord Server Github Page](#moni-heichou-discord-server-github-page)
  - [Table of content](#table-of-content)
  - [What are we currently working on?](#what-are-we-currently-working-on)
  - [The server structure](#the-server-structure)
  - [The different roles and how to achieve them](#the-different-roles-and-how-to-achieve-them)
    - [Moderation Roles](#moderation-roles)
    - [Level Roles](#level-roles)
    - [Selectable Roles](#selectable-roles)
      - [Channel Visibility](#channel-visibility)
      - [Notifcation Roles](#notifcation-roles)
      - [Gender](#gender)
      - [Social Status](#social-status)
    - [Any Other Roles](#any-other-roles)
  - [How do we handle rule violations?](#how-do-we-handle-rule-violations)
    - [§1 General Rules](#1-general-rules)
    - [§2 Interaction with other Users](#2-interaction-with-other-users)
    - [§3 Posting Content](#3-posting-content)
    - [§4 Using the voice channels](#4-using-the-voice-channels)
  - [Commands](#commands)
    - [Active Bots](#active-bots)
    - [Standard users](#standard-users)
    - [Admin users](#admin-users)
  - [Events](#events)
  - [Terms and their explanation.](#terms-and-their-explanation)
    - [1. Role reactions](#1-role-reactions)
    - [2. NSFW (Not Safe for Work)](#2-nsfw-not-safe-for-work)
  - [Image Links](#image-links)
  - [Copyright Notices](#copyright-notices)
>>>>>>> 2a6acda (Git Push Test)
  - [Commands](#commands)
    - [Active Bots](#active-bots)
    - [Standard users](#standard-users)
    - [Admin users](#admin-users)
  - [Events](#events)
  - [Terms and their explanation.](#terms-and-their-explanation)
    - [1. Role reactions](#1-role-reactions)
    - [2. NSFW (Not Safe for Work)](#2-nsfw-not-safe-for-work)
  - [Image Links](#image-links)
  - [Copyright Notices](#copyright-notices)
</details>

--- 
<!-- Current Progress -->
## What are we currently working on?

Under this section we post the current status of what we are working on. 

- [x] organize Roles
- [ ] create channels with different swearing word levels
- [x] add Arcane bot for levelling
  - only users with a certain level are candites for mods or etc. (replace classic level system)
- [x] create a stage channel for events
- [x] self-selecteble roles
- [ ] potentially replace YAG role reactions with Dyno role reactions
- [x] reorganize channels
- [ ] create new rules
- [ ] welcome messages (Dyno bot)

---
<!-- Structure -->
## The server structure

The server is structered in different voice and text channels. To keep things organized for everybody only with certain roles certain channels will be displayed. For example is the `『🔞』18-plus-content` channel only for users with the `18+ Content` role visible. 
>The following table shows every available channel and their particular usecase. 

| Caterogy          | Channel             | Usecase                                                                                                   |
| ----------------- | ------------------- | --------------------------------------------------------------------------------------------------------- |
| *ServerStats*     | 〔👥〕Users: (x)     | The current member count                                                                                  |
|                   | 〔🤖〕Bots: (x)      | The current bot count                                                                                     |
| *Important*       | 〔📝〕regeln         | The current rules                                                                                         |
|                   | 〔🔔〕ankündigungen  | Information about current changes and events                                                              |
|                   | 〔🎉〕willkommen     | Welcome messages for new users                                                                            |
|                   | 〔❓〕server-info    | General information about the server as a whole                                                           |
|                   | 〔🏷〕rollen         | A channel where users can select roles for themselves                                                     |
| *Main Chat*       | 『💬』lobby          | The regular chat without any specific topic                                                               |
|                   | 『🔞』18-plus-lobby  | NSFW[[²]](#2-nsfw-not-safe-for-work) is allowed in this channel                                           |
|                   | 『⚠』fvck-humanity  | Life sucks sometimes                                                                                      |
|                   | 『👾』bot-commands   | The only channel where bot commands are allowed                                                           |
| *Moni Heichou*    | 『⛈』brainstorming  | Thoughts from Moni Heichou                                                                                |
|                   | 『🧡』fans-only      | Updates regarding new books                                                                               |
|                   | 『✍️』ask-the-author | Questions and feedback from the community to Moni Heichou                                                 |
| *General - Voice* | 🔇muted🔇             | A channel for those who want to participate in a voice chat but do not have or want to use a microphone   |
|                   | 『🎤』Events         | This channel is only for events with a host. Featureing silent joins and leaves + only certified speakers |
|                   | 『👥』VC #1          | A voice chat for general use                                                                              |
|                   | 『👥』VC #2          | Same as  `『👥』Lounge #1`                                                                                 |
|                   | 『🔒』Private VC     | A voice chat for general use, but limited to a smaller number of users                                    |
|                   | 『🎧』Music [BOTS]   | A voice chat to enjoy some nice music with your friends                                                   |
| *Staff Rooms*     | 『🆘』support        | Creation of support tickets                                                                               |
|                   | 『👷』staff          | A chat for the staff                                                                                      |
|                   | 『🗃️』logs           | A chat for logs produced by bots                                                                          |
|                   | 『🔧』Support        | A voice chat related to support tickets                                                                   |
|                   | 『🕒』Waiting        | A channel where users wait for their voice support                                                        |
|                   | 『🎓』Staff Meetings | A voice chat for staff members                                                                            |

---
<!-- Roles -->
## The different roles and how to achieve them

We offer a selection of different roles to every user. Some roles are self-selectable like for example `XX`. These can be applied and removed through role reactions[[¹]](#1-role-reactions). On the other hand some roles have to be applied through a staff member. Besides that bots also create roles for theirselves. These exists, but are not listed below. 
<br>As mentioned before a few roles also reveal channels or categories. This is used mostly for moderation roles, but also for the `『⚠』fvck-humanity` channel. 

> <br> *The categories and roles are sorted by hierarchy.

### Moderation Roles

Only with these roles are truly a member of the staff team. They have the authority over the server and can supervise the roles below them. 

| Role               | Abilities                                                         |
| ------------------ | ----------------------------------------------------------------- |
| [👑]Owner           | Overall managment + Decision-making authority                     |
| [🚨]Deputy          | Substitute of the Owner                                           |
| [🌐]Alpha Moderator | Channel Managment + Supervision of the Moderators + Support       |
| [🌀]Moderator       | Channel Managment, Training of the trial mods + their supervision |
| [❓]Trail Mod       | Basic Managment + Support                                         |
| Server Staff       | General role for the whole server moderation team                 |

### Level Roles

These roles are applied automatatically by the Arcane Bot and provide special perks. In order to earn a role who have to particpate activly. A full leaderboard of every participant can be found here: [Link to Leaderboard]()

> However messages in the channels listed below do not give the user any xp. 

- `support` 
- `logs` 
- `『👾』bot-commands`

| Role         | Abilities                                                        | Required XP |
| ------------ | ---------------------------------------------------------------- | ----------- |
| [💯]Level 100 | Own the ability to speak in the event channel + everything below | 502,500     |
| [📈]Level 75  | Partipicating in giveaways + everything below                    | 283,125     |
| [✨]Level 50  | Early acces to books + everything below                          | 126,250     |
| [💓]Level 25  | Votes on community questions count twice                         | 31,875      |
| [🔥]Level 10  | Vote for new server features                                     | 5,250       |

### Selectable Roles

These roles can be selected by the user himself through role reactions in the `〔🏷〕rollen`-channel. 

#### Channel Visibility 

The roles below help you to select which channles you can see and chat in. 

| Role        | Catogory/Channel Reaveal                     |
| ----------- | -------------------------------------------- |
| 18+ Content | -『🔞』18-plus-lobby <br> -『⚠』fvck-humanity |
| Chat        | -『💬』lobby                                  |
| True Fan    | - Moni Heichou *(Category)*                  |


#### Notifcation Roles

The roles below show which options do you have to opt in and opt out certain notifications. 

| Role | Type of Information |general -role also has to be selected) |
| [🍬]Giveaway | - Upcoming giveaways (partipicating only for level 75+) |
| [👏]Welcome Gang | - Welcome new members to the server | 

#### Gender

Under this section we offer the users to select their gender identity. 

<details>
<summary>Non-Binary Gender identities</summary>

> We are aware of the fact that many other genders exist. However, we decided to keep the amount of roles in this section as low as possible and only offer `XXX` for non-binary gender identities. Please consider to write down your pronouns in your Discord™ biography if you wish so. 
</details>

| Role | Meaning    |
| ---- | ---------- |
| XX   | Female     |
| XY   | Male       |
| XXX  | Non-Binary |

#### Social Status

If you want to share your social status please consider using the roles below. 
- Simp 
- Lost 
- Married

### Any Other Roles

| Role        | Achieving                         | Ability                                                                                                    |
| ----------- | --------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [👾] Bots    | Be a bot                          | Bot specific                                                                                               |
| [✅]Verified | Accept the rules                  | Reveal any channel besides the [selectable channels](#channel-visibility) above or the staff-only channels |
| everyone    | Automatically given to every user | None                                                                                                       |

---
<!--- Rules -->

## How do we handle rule violations?

Here are the current rules and their consequences for the Server listed. 
> These rules can also be found in the specified channel on the server itself. 

### §1 General Rules

1. The server team is allowed to judge on their own discretion. Your acces can be removed for any reason at any time.
2. It is forbidden to avoid a ban with a second account
3. As soons as you click on the checkmark-reaction below the message on the discord server and gain acces to the server you accpet the rules
4. Changes to the rules can be applied at any time and will be implented immediatly
5. Everybody who gets banned or muted has the right to fill out a form and apply for an unban or unmute
6. The general Discord™ [Community Guidelines](https://discord.com/guidelines) and [Terms of Service](https://discord.com/terms) apply of course as well to this server

### §2 Interaction with other Users

- Treat other users with respect
  - Especially the staff team
- Try to avoid all kind of unnecessary drama
- Keep toxicity and swearing to a certain level
- Avoid unnecessary pings
- The distribution of extremistic thought in any way is forbidden, This includes political and ideological attitudes and the spreading of misleading information
- Hate speech is unacceptable and will not be tolerated
- Do not threaten to use force and/or harm others
- Do not spread viruses, malware,other similar suspicious code/programs or attempt to fish, hack or DDoS others
- The only two languages that are allowed on the server are German and English

### §3 Posting Content

- Use caplocks, emotes and etc. in comman sense
- Do not spam
- Use the `spoiler`-option if it is neccessary
- Forbidden content
  - NSFW[[²]](#2-nsfw-not-safe-for-work) (except the 18+ channels)
  - Sexualization of minors
  - Gore or animal cruelty
  - Selfpromotion
  - Sales promotion
  - Promotion of illegal material and/or activities
  - Promotion of other Discord™ Servers

### §4 Using the voice channels

- 

---
<!--- Bot Commands -->
## Commands

<!--- <details>
<summary>Bots</summary>            --->

### Active Bots

> Here we list any actively used bot on the server. 

| Bot                                        | Usage                     |
| ------------------------------------------ | ------------------------- |
| [Dyno](https://dyno.gg/)                   | Moderation,               |
| [YAGPDB](https://yagpdb.xyz/)              | Moderation                |
| [Xenon](https://xenon.bot/)                | Backups                   |
| [Arcane](https://arcane.bot/)              | Leveling                  |
| [ServerStats](https://serverstatsbot.com/) | General server statistics |
| [TicketTool](https://tickettool.xyz/)      | Support ticket creation   |
| [Hydra](https://hydra.bot/)                | Play music                |

</details>

### Standard users

### Admin users


---
<!--- Past Events -->
## Events

---
<!-- Explanation of terms -->
## Terms and their explanation. 

Under this section we explain certain terms which might not be familiar with the majority of users. 

### 1. Role reactions

Role reactions are reactions under messages which allow users to self select a role. The actual action is performed by bots, so the roles are applied immediatly. 

### 2. NSFW (Not Safe for Work)

NSFW stands for "Not Safe for Work" and is another term for adult content. 

---
<!-- Image Sources -->
## Image Links

- [Welcome Image](https://imgur.com/a/tx0B0C9)
- 

---
<!--- Copyright -->
## Copyright Notices

©️ 2022 [OutofSpace](https://www.youtube.com/watch?v=dQw4w9WgXcQ "👑Lines of Code👑")