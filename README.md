# Rage to win

## Založení projektu [11.10.2024]
Vyber základních textur a stažení prvních potřebných materiálů. Zajištění podstatných pluginů pro správné fungování projektu.

## Sphere (vesmírná část) [12.10.2024]
Založení koule, do které byla přidána 4K textura hvězd z vnitřní strany. Zároveň byla přidána vlastnost *SkyAtmosphere Light Disk Luminance* pro světlo ve tmě.
Na závěr došlo k použití Directional Light, které osvětluje směrem od slunce pro simulaci svitu.
![image](https://github.com/user-attachments/assets/48a97b73-3cc0-4876-9e07-88307c8c059f) ![image](https://github.com/user-attachments/assets/cde79b57-db35-4fad-a391-25d6b854d3fc) ![image](https://github.com/user-attachments/assets/c2d999d4-bea7-48e9-b3b0-bef62810b6b6)




## Land (pozemní část) [19.10.2024]
Pozemní část je tvořena pomocí funkce Landscape, díky které bylo možné vytvořit prostor výrazně vyvýšený oproti zbytku mapy zaplavené vodou.
V této části se také nachází graficky nenadesignovaný protál mezi světy, řešený prostřednictvím hitboxu, který hráče přesune na druhý level(mapu).
![image](https://github.com/user-attachments/assets/537222c1-bfd3-4173-b8bd-02a21cb75471)

![image](https://github.com/user-attachments/assets/1271fd07-864d-44b2-aca0-f3419452a7f6)

## Základní pohyb [3.11.2024]
Byl vytvořen základní charakter, který se pohybuje za pomoci kláves WASD, skáče při stisknutí mezerníku a umožňuje rozhlížení se pomocí myši na základě osy X a Y. Zároveň samotný svět obsahuje základní fyzikální vlastnosti pro návrat na povrch při výskoku.
![image](https://github.com/user-attachments/assets/92447555-f98b-41d6-b974-01d3f547bbf8)

## Importace a aplikace Dust_Devil textur [4.11.2024]
Importování prvků do projektu pro budoucí použití v trap systému a zakomponování do prostředí.


## Attack animace [9-10.11.2024]
Přidání animace útoku probíhalo pomocí implementace "input key node," díky kterému můžeme na základě podmínky, zda animace probíhá nebo už skončila, navázat další animaci. Tím zabraňujeme nahromadění animací a nepřirozenému pohybu. Dále se pomocí náhodného čísla můžeme rozhodnout, zda se provede animace A nebo B.
![image](https://github.com/user-attachments/assets/cbc66c04-be60-4b7a-b121-ae639bf90842)
![image](https://github.com/user-attachments/assets/9ec0225a-1941-4f84-b70a-b397639e50da)

## Lock-On na nepřítele [15-17.11.2024]

Přidání základního Lock-On (zamknutí pohledu na nepřítele). Pro usnadnění zasažení nepřítele při pohybu.
![image](https://github.com/user-attachments/assets/5687d0f8-b5eb-4481-a989-0cfa2569e1a8)


## Vylepšení Lock-On [18-19.11.2024]
Opravení Lock-On otočených animací při jeho spuštění a celého průběhu za pomoci Blend Space a jeho aplikování do Animation Blueprintu herní postavy
![image](https://github.com/user-attachments/assets/116ca63a-67f8-4611-8002-d9534b82032e)

## Vytvoření widgety DC(death counter) a game instance [21-22.11.2024]
Vytvoření death counteru s implementací funkce přenosu dat mezi úrovněmi (Game Instance)
![image](https://github.com/user-attachments/assets/8c176df6-927c-4177-aad4-0748258a2050) ![image](https://github.com/user-attachments/assets/cdd5bdb7-8d30-418c-a10b-d098bbb3a1fd)

## Health System [24.11.2024]
Přidání health systému (na základě tří hodnot určujících maximální zdraví, minimální zdraví a aktuální zdraví) společně s widgetou indikující aktuální stav zdraví.
![image](https://github.com/user-attachments/assets/1310e484-63e5-475e-b46b-5f53e85b5e59)

## Herní menu [28-29.11.2024]
Vytvoření menu ve hře, které se skládá ze dvou částí: jedna pro start a nastavení hry před jejím začátkem a druhá pro akce dostupné během samotné hry. Menu zahrnuje možnosti: 1) start hry/pokračování ve hře, 2) nastavení hry, 3) opuštění hry, 4) úprava hlasitosti a grafického rozlišení.
Celá tato logika je založena na klíčovém nodu Get Game User Settings, pro práci s nastavením hry.
Na závěr došlo k vytvoření logiky pro vložení do viewportu ve hře a práci s volným a uzamčeným kurzorem při jeho vyvolání.
![image](https://github.com/user-attachments/assets/abea3a0f-3fc4-47f6-8693-b4fff63976f0)
![image](https://github.com/user-attachments/assets/24ebba7e-1630-42f0-ad9d-b4ed44d5c1e0)
![image](https://github.com/user-attachments/assets/324d207f-6bbd-4e82-baaf-7786e6ad70d3)

## Přidání nepřítele [3.12.2024]
Naimportování postavy nepřítele do projektu a vytvoření základní logiky pohybu na pozici hráče pomocí PawnSensing.
![image](https://github.com/user-attachments/assets/d0d64359-3452-4803-ad34-d94d5ce5ac78)

## Importování textur do SpaceMap [8.12.2024]
Stažení a integrace texturovaných objektů do projektu v rámci sekce Space Map.
![image](https://github.com/user-attachments/assets/ab2d84e0-8f81-4bf8-9f4b-4d5290258dbb)




