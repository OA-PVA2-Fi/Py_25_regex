# PVA2 - Programování a vývoj aplikací
## Cvičení 25: Regulární výrazy

Regulární výrazy a programy uložte v repozitáři.

### 1
Najděte a otestujte správnost na vstupech:
* všechna číslice v řetězci. 
* všechny malé písmena v řetězci.
* všechny velké písmena v řetězci
* všechny číslice, malé i velká písmena
* pouze sudá čísla v řetězci
* Všechna slova obsahující alespoň tři samohlásky

Příklad vstupů pro otestování funkčnosti
* 777 888 666 444
* 789987456
* +420 777 666 555
* Loreim Ipsum in Da House
* 451 stupnu Fahrenheita
* 101 dalmatinu

### 2
- Extrahuj všechna data ve formátu dd/mm/yyyy: `10/12/2024, 01-01-2024, 23/07/2023, 12.12.2024`
- Najdi všechna slova začínající na `a` v řetězci `apple banana apricot orange avocado`
- Najdi všechna slova obsahující číslici `abc123, def456ghi, 789, no_digits_here`
- Najdi všechny věty končící otazníkem. `How are you? I am fine. What about you? Sure!`

### 3
Náš systém vyžaduje od uživatele zadání uživatelského jména. Uživatelské jméno smí obsahovat pouze malá písmena a smí být maximálně 8 znaků dlouhé. Požádej uživatele o zadání uživatelského jména a pomocí regulárního výrazu vyhodnoť, zda je zadané správné.

### 4
Pro školní systém definujte ověření na školní emailové adresy.
* Na prvním místě může být jedno písmeno D, B nebo C
* Druhé až páté místo jsou číslice
* Za zavináče je uveden výraz oaopava.cz

Například: D40123@oaopava.cz	

### 5 PSČ
- Naprogramuj validaci českého formátu PSČ
- Najdi pouze správná česká PSČ: `123 45, 54321, 987 65, 12-345, 5432, 123  32`
- 

### 6
Vytvořte program pro kontrolu správnosti SPZ vozidla.

* Na prvním místě je číslo.
* Na druhém místě písmeno, které označuje kraj.
* Na třetím místě je číslo nebo písmeno.
* Na čtvrtém místě je mezera a následuje čtveřice čísel.

Vzorek pro otestování:
Správný formát: 4P6 4482, 6A2 6635, 2AD 3424, 4C3 5025
Špatný formát: 3A 1122, A1 34567, 934 8842

B) Rozšiřte kontrolu SPZ na povolení pouze znaku kraje: A, B, C, E, H, J, K, L, M, P, S, T, U, Z.


### 7
V Česku máme standardně devítimístná telefonní čísla. Napiš regulární výraz, který sedí na “naše” telefonní čísla.

Často se telefonní číslo rozděluje na trojčíslí oddělené mezerou. Uprav svůj výraz tak, aby odpovídal číslům s mezerou i bez mezery.

Rozšiř regulární výraz tak, aby bylo možné před telefonní číslo přidat mezinárodní předvolbu (v našem případě +420), aby nám mohli volat i lidé ze zahraničí. 

Vzor pro otestování:
553123987
553 312 987
+420 553 312 987



### 8
Definujte regulární výraz pro kontrolu emailové adresy.

* Každá emailová adresa může mít před zavináčem znaky americké abecedy, číslice, tečky, podtržítko
* Doména a TLD musí obsahovat alespoň dvě písmena.
