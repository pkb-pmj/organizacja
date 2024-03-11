# Minecraft development

## Serwer

Serwery są nieodłączym elementem Minecrafta. Dzięki nim możemy cieszyć się z gry w czasie rzeczywistym z innymi graczami. To one również umożliwiają nam na urozmaicanie rozgrywki za pomocą pluginów.

### Silnik

Istnieje wiele silników, na których można uruchomić serwer. Każdy z nich ma swoje wady i zalety

#### Vanilla

[Java Edition](https://www.minecraft.net/pl-pl/download/server)

[Bedrock Edition](https://www.minecraft.net/en-us/download/server/bedrock)

Podstawowy silnik. Nie obsługuje modów ani pluginów. Wydawany przez Mojand z każdą wersją gry Minecraft.

#### CraftBukkit

[CraftBukkit](https://getbukkit.org/download/craftbukkit)

Pierwszy popularny silnik. 

#### Spigot

[Spigot](https://getbukkit.org/download/spigot)

Silnik bazujący na CraftBukkit. Przez długi czas najpopularniejszy silnik.

#### Paper

[Paper](https://papermc.io/)

Silnik bazujący na Spigot, skupiający się na wydajności. Obsługuje pluginy.

#### Forge

[Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)

Silnik stworzony do rozszerzania silnika vanilla po przez modyfikacje.

## IDE

Rekomendowane narzędzie IDE do pracy z pluginami i modami.

[JetBrains InteliJ IDEA](https://www.jetbrains.com/idea/)

## Launcher Minecraft

Istnieje wiele rodzajów launcherów gry Minecraft, które różnią się interfejsem graficznym i możliwościami takimi jak ułatwione wgrywanie pluginów i modów lub wymaganie zakupienia gry bądź nie.

### Portablemc

Portablemc to lekki launcher CLI w wersji zarówno non-premium jak i premium, służący do łatwej instalacji mod loaderów.

[Portablemc](https://pypi.org/project/portablemc/)

#### Instalacja

Za pomocą menadżera pakietów *pip* pobieramy najnowszą wersję launchera.

##### Windows

```bash
pip install --user portablemc[certifi]
```

##### Linux

```bash
pip install --user portablemc
```
