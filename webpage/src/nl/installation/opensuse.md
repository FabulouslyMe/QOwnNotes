# Installeer op openSUSE Linux

<installation-opensuse/>

<!-- <Content :page-key="getPageKey($site.pages, '/installation/ubuntu.md')" /> -->


## Minden openSUSE verzión

U kunt QOwnNotes installeren met de tool [OBS Package Installer](https://github.com/openSUSE/opi).

Voer de volgende shell-opdrachten uit als root om `opi` te installeren:

```bash
zypper install opi
```

Installeer dan QOwnNotes ermee:

```bash
opi qownnotes
```

::: warning
Deze tool zal de hele OBS-service doorzoeken, dus zorg ervoor dat u `qownnotes` kiest en niet `qownnotes-lang` als daarom wordt gevraagd.

Controleer ook of de gekozen repo de officiële `home:pbek:QOwnNotes` is en niet die van een derde partij.
:::

::: tip
U moet de optie kiezen om de repository na installatie te behouden om updates te krijgen.
:::

## openSUSE Leap 15.4

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/15.4/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/15.4)

## openSUSE Leap 15.3

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_15.3/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_15.3)

## openSUSE Leap 15.2

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_15.2/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_15.2)

## openSUSE Leap 15.1

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_15.1/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_15.1)

## openSUSE Leap 15.0

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_15.1/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_15.0)

## openSUSE Leap 42.3

Voer de volgende shell-opdrachten uit als root om de repository te vertrouwen.

```bash
su -
rpm --import http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_42.3/repodata/repomd.xml.key
```

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_42.3/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_42.3)

## openSUSE Leap 42.2

Voer de volgende shell-opdrachten uit als root om de repository te vertrouwen.

```bash
su -
rpm --import http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_42.3/repodata/repomd.xml.key
```

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_42.3/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Leap_42.2)

## openSUSE Tumbleweed

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Tumbleweed/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/openSUSE_Tumbleweed)


## SLE 12 SP3 Backports

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/SLE_15/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/SLE_12_SP3_Backports)

## SLE 15

Voer de volgende shell-opdrachten uit als root om de repository toe te voegen en vanaf daar QOwnNotes te installeren.

```bash
zypper addrepo -f http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/SLE_15/home:pbek:QOwnNotes.repo
zypper refresh
zypper install qownnotes
```

[Directe download](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/SLE_15)
